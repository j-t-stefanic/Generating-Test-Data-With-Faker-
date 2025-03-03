# Generating-Test-Data-With-Faker-
Create sales transaction test data using Faker and Pandas.

-The purpose of this project was to create a sample of test sales transactions that can be used in other projects such as writing Dataframes to csv files,, as well as performing Exploratory Data Analysis.

-The code generates randomized transactions that include the following elements:
--'transaction_id': fake.uuid4()
--'gender': random.choice(['Male', 'Female', 'Unspecified'])
--'product_name': fake.word(ext_word_list=['Milk','Eggs','Bread','Cheese','Chicken Breast','Ground Beef','Salmon','Pasta','Rice','Cereal',
'Apples', 'Bananas', 'Grapes', 'Potatoes','Onions','Carrots','Tomatoes','Lettuce','Rice Bowls','Yogurt','Butter','Olive Oil']
--'quantity': random.randint(1, 5)
--'unit_price': round(random.uniform(50, 2000), 2)
--'transaction_date': fake.date_between(start_date='-30d', end_date='today')
--'payment_method': random.choice(['Credit Card', 'Debit Card', 'Cash', 'Online Payment'])

