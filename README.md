This dataset was downloaded from kaggle, which holds periodic introductory competitions
using this data. It was originally compiled by De Cook for educational purposes. Skim this
article for some tips on using this dataset: De Cook 2011.
user_features.csv This file consists of features generated from the original kaggle dataset.
• user_id: this is a number uniquely identifying each user
• packaged cheese to frozen juice: Columns 2:135 consistent of the name of food
categories (called aisles in the instacart data). The value in each entry of these columns
is the number of items from that category ordered by each customer throughout the entire
year. This count is a little imprecise because it does not differentiate the quantity of
items per order (which is unavailable in this data).
• Saturday to Friday: Columns 136:142 correspond to days of the week. The values
correspond to the number of orders each user made on a given day of the week.
2. Official Instacart data:
• aisles.csv: This file identifies the aisles (food categories) that correspond to each
aisle_id
• departments.csv: This file identifies the departments (a very rough category of product)
that correspond to each department id. Departments and Aisles form a hierarchy, each
food item is contained within an aisle, and each aisle is contained within a department.
1
• products.csv contains information on each product, including the product name, the
aisle, and the department
• orders.csv contains high level information about each order, including the user_id,
the order_id, the order number of that user (whether it is the user’s 1st, 3rd, or 10th
order etc), the day of week and hour of the day the order was made, and the number of
days elapsed since their previous order
• all_order_products.csv contains detailed information on each specific order, including
all the products in that order and the order in which those products were added.
