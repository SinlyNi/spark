# spark
-----
- about spark mllib
- decision tree
- decision tree model toDebugString transfor to json data
-----
-----
- input data

```javascript

DecisionTreeModel classifier of depth 4 with 25 nodes
If (feature 25 <= 0.0)
If (feature 0 <= 1180.0)
If (feature 24 <= 4.0)
If (feature 22 <= 1.0)
Predict: 1.0
Else (feature 22 > 1.0)
Predict: 1.0
Else (feature 24 > 4.0)
If (feature 4 <= 0.0)
Predict: 0.0
Else (feature 4 > 0.0)
Predict: 1.0
Else (feature 0 > 1180.0)
If (feature 1 <= 20.0)
If (feature 2 <= 74.0)
Predict: 1.0
Else (feature 2 > 74.0)
Predict: 0.0
Else (feature 1 > 20.0)
Predict: 0.0
Else (feature 25 > 0.0)
If (feature 0 <= 200.0)
If (feature 18 <= 2.0)
If (feature 9 <= 0.0)
Predict: 1.0
Else (feature 9 > 0.0)
Predict: 0.0
Else (feature 18 > 2.0)
Predict: 0.0
Else (feature 0 > 200.0)
If (feature 0 <= 800.0)
If (feature 11 <= 0.0)
Predict: 1.0
Else (feature 11 > 0.0)
Predict: 1.0
Else (feature 0 > 800.0)
Predict: 1.0

```
-----

- output data

```javascript

[ {
  "name" : "DecisionTreeModel classifier of depth 4 with 25 nodes"
}, {
  "name" : "  feature 25 <= 0.0",
  "values" : "",
  "children" : [ {
    "name" : "  feature 0 <= 1180.0",
    "values" : "",
    "children" : [ {
      "name" : "  feature 24 <= 4.0",
      "values" : "",
      "children" : [ {
        "name" : "  feature 22 <= 1.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      }, {
        "name" : "  feature 22 > 1.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      } ]
    }, {
      "name" : "  feature 24 > 4.0",
      "values" : "",
      "children" : [ {
        "name" : "  feature 4 <= 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 0.0"
        } ]
      }, {
        "name" : "  feature 4 > 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      } ]
    } ]
  }, {
    "name" : "  feature 0 > 1180.0",
    "values" : "",
    "children" : [ {
      "name" : "  feature 1 <= 20.0",
      "values" : "",
      "children" : [ {
        "name" : "  feature 2 <= 74.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      }, {
        "name" : "  feature 2 > 74.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 0.0"
        } ]
      } ]
    }, {
      "name" : "  feature 1 > 20.0",
      "values" : "",
      "children" : [ {
        "name" : "Predict: 0.0"
      } ]
    } ]
  } ]
}, {
  "name" : "  feature 25 > 0.0",
  "values" : "",
  "children" : [ {
    "name" : "  feature 0 <= 200.0",
    "values" : "",
    "children" : [ {
      "name" : "  feature 18 <= 2.0",
      "values" : "",
      "children" : [ {
        "name" : "  feature 9 <= 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      }, {
        "name" : "  feature 9 > 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 0.0"
        } ]
      } ]
    }, {
      "name" : "  feature 18 > 2.0",
      "values" : "",
      "children" : [ {
        "name" : "Predict: 0.0"
      } ]
    } ]
  }, {
    "name" : "  feature 0 > 200.0",
    "values" : "",
    "children" : [ {
      "name" : "  feature 0 <= 800.0",
      "values" : "",
      "children" : [ {
        "name" : "  feature 11 <= 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      }, {
        "name" : "  feature 11 > 0.0",
        "values" : "",
        "children" : [ {
          "name" : "Predict: 1.0"
        } ]
      } ]
    }, {
      "name" : "  feature 0 > 800.0",
      "values" : "",
      "children" : [ {
        "name" : "Predict: 1.0"
      } ]
    } ]
  } ]
} ]

```
----------
