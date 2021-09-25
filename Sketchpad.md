consider the starting place to be an android app built for a **Retail Store**. What all backend components will it need?
- A way to define Object / Item 
- A way to define transaction (buy / sell)
- A ledger
- A way to define inventory
- A way to define Staff (might not be needed in bare-bones version)

Once we have components built, we need a way to build the app on top of components
- each component should be treatable as an interface, the user can extend interface to add functionality

Once, the app is written
- there should be a way to package the components
- And possibly create kubernetes project along with components

**overall pipeline**
- User builds an app using our components
- The system generates a kubernetes project, along with software package
- The kubernetes project can be deployed on our hosted instances Or wherever use wants



