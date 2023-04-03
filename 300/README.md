# 300 - Building Our Application

## 100 - Your Baserow Account

Go to the login page, by https://baserow.io/login

Once logged in successfully in https://baserow.io/ click on **Create new** (if you have not already done so), choose **Database**.

(Re)name the database, starting from scratch, to **Servings** and click Add Database.

Under the database "Servings" in the left-hand column of your page, you will see at table (*Table*), rename it to **Cereals**.

It can be visited at https://baserow.io/database/59531/table/154662

In **Grid View**, double click on the column(s) to change their names as follows:

| Atom | Size | Color |
| -- | -- | -- |
| Mi | 5 | #FFFFFF |
| OF | 5 | #FFFFFF |
| MG | 5 | #FFFFFF |
| OM | 5 | #FFFFFF |

Where:
- Mi = Milk
- OF = Oat Flakes
- MG = Multigrain
- OM = Oat Meal

![Baserow_Servings_Cereals](https://user-images.githubusercontent.com/1499433/229465862-49a66ae9-c874-4d23-aab9-51b4b1feeb94.png)

*NOTE*: This should ultimately result in a JSON data file like:
 
 ```
 {
  "nodes": [
    {"atom": "Mi", "size": 5, "color": "#FFFFFF"},
    {"atom": "OF", "size": 5, "color": "#FFFFFF"},
    {"atom": "MG", "size": 5, "color": "#FFFFFF"},
    {"atom": "OM", "size": 5, "color": "#FFFFFF"}
  ],
  "links": [
    {"source": 0, "target": 1,  "bond": 1},
    {"source": 1, "target": 2,  "bond": 1},
    {"source": 1, "target": 3,  "bond": 1}
  ]
}
 ```
 
 MORE ...
