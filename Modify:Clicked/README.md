# Modify Button as Clicked Override Method
With this pieces of codes you can insert a modify button into your form.

In order to insert a modify button you must:
1. Create a Form(Orders) and a ChildForm(AddOrders) with the same data source (Orders)
2. Create a MenuItemButton in the Design section of the Form
3. Set MenItemButton properties to Edit
4. Create a MenuItem with the ChildForm and set to edit
5. Create an override method clicked in the MenuItemButtom  with the code that you can find in the repository.
6. Create a ClassDeclaration and Init Methods (same code as repository) in the ChildForm's section methods
7. Create an ExecuteQuery Method (same code as repository) in the ChildForm's data source methods
