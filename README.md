Task: predict whether users will like a social network post?

Input data
The dataset prepared by the VK team is available at https://cloud.mail.ru/public/oezf/KJSaChzoz .

It consists of several CSV files:

**topics.csv** — contains information about social network posts. Each entry is characterized by text and image attributes.

**users.csv** — contains information about users. Each user is characterized by date of birth, gender and city ID.

**train.csv** — contains information about user interaction social network posts. The type of interaction is equal to "L" if user liked the record, and "D" if he or she didn't like the record.

**test.csv** — contains the ids of the records and users for whom you have to predict the type of interaction.