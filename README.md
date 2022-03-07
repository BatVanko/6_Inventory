# 6_Inventory
Create a class Inventory. The __init__ method should accept only the __capacity: int (private attribute) of the inventory. You can read more about private attributes here. Each inventory should also have an attribute called items - empty list, where all the items will be stored. The class should also have 3 methods:
•	add_item(item: str) - adds the item in the inventory if there is space for it. Otherwise, returns 
"not enough room in the inventory"
•	get_capacity() - returns the value of __capacity
•	__repr__() - returns "Items: {items}.\nCapacity left: {left_capacity}". The items should be separated by ", "
