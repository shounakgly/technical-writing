# Defining Expressions Using SMML
You can use expressions in SMML schema files to define and identify joins between objects. These joins are referenced using the elements `expressionTemplate` and `expressionObjects`. 

In SMML schema files, `expressionTemplate` defines and stores the join's expression, which can be viewed and edited using the Expression Editor. The `expressionObjects` element names the objects that are referenced in the join expression. For example: 

```
"physicalExpression": {
                        "expressionTemplate": " TIMESTAMPDIFF( SQL_TSI_DAY , %1, %2)",
                        "expressionObjects": [
                           "physicalColumn:Sample App Data (ORCL).SAMPLE.F13 Rev\\. (Order Dt Join).Order_Day_Dt",
                           "physicalColumn:Sample App Data (ORCL).SAMPLE.F13 Rev\\. (Order Dt Join).Ship_Day_Dt"
                        ]
                     }
 ```
 For information on expression elements and the Expression Editor, see [Expression Editor Reference](https://docs.oracle.com/pls/topic/lookup?ctx=en/middleware/bi/analytics-server/smml-oas&id=OASSM-GUID-1A790ED8-A783-4C55-B131-C738109BD8DA).
