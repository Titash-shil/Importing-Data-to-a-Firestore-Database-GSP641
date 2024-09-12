# Importing Data to a Firestore Database || [GSP642](https://www.cloudskillsboost.google/focuses/8392?parent=catalog) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

### Run the following Commands in CloudShell

```
gcloud config set project $DEVSHELL_PROJECT_ID

gcloud firestore databases create --location=nam5

git clone https://github.com/rosera/pet-theory

cd pet-theory/lab01

npm install @google-cloud/firestore

npm install @google-cloud/logging

curl https://raw.githubusercontent.com/Titash-shil/Importing-Data-to-a-Firestore-Database-GSP641/main/Qwiklab_Explorers_TS_importTestData.js > importTestData.js

npm install faker@5.5.3

curl https://raw.githubusercontent.com/Titash-shil/Importing-Data-to-a-Firestore-Database-GSP641/main/Qwiklab_Explorers_TS_createTestData.js > createTestData.js

node createTestData 1000

node importTestData customers_1000.csv

npm install csv-parse

node createTestData 20000

node importTestData customers_20000.csv
```

# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
