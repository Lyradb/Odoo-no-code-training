### Odoo Training for No-Code Developers
This training is designed for **no-code developers** to help them create, customize, and automate processes in Odoo without writing any code. You'll learn how to use Odoo Studio and other built-in features, enabling you to effectively tailor Odoo to fit business needs.

---

## **Outline**

1. **Introduction to Odoo and No-Code Development**
2. **Customizing Odoo Forms Without Code**
3. **Automating Workflows in Odoo**
4. **Creating Reports and Dashboards Without Code**
5. **Creating a New No-Code Application in Odoo**
6. **Managing Security and Access Control**

---

### **Module 1: Introduction to Odoo and No-Code Development**

Odoo is a modular ERP system that allows businesses to manage everything from accounting to CRM and inventory. As a no-code developer, you'll use tools like **Odoo Studio** to customize forms, views, and automate workflows without writing code.

#### **1.1 Overview of Odoo Studio**
Odoo Studio is a drag-and-drop interface for no-code developers:
- Customize existing forms and views.
- Create new fields, workflows, and applications.
- Automate actions and business processes.

---

### **Module 2: Customizing Odoo Forms Without Code**

#### **Objective**: Customize a form in the Sales module by adding a new field.

**Steps**:

1. **Open the Sales App**:
   - Navigate to the **Sales** app from the Odoo dashboard.
   - Open any existing **Sales Order**.

2. **Activate Odoo Studio**:
   - Click the **Studio** icon (found in the top right of the screen).
   - The screen will enter a drag-and-drop customization mode.

3. **Add a New Field**:
   - On the right-hand panel, locate the **Fields** section.
   - Drag the **Selection** field (a dropdown field) and drop it into the Sales Order form where you want the new field to appear.

4. **Configure the New Field**:
   - A dialog box will appear. Enter a label for the field (e.g., **Sales Source**).
   - Define the selection options (e.g., Website, Referral, Social Media).
   - Click **Confirm** to save the field.

5. **Save the Form**:
   - Click **Save** in Studio, then **Exit** to see the updated Sales Order form with the new field.

**Result**: Your form is now customized, and users can select from the predefined options in the new field.

---

### **Module 3: Automating Workflows in Odoo**

#### **Objective**: Automate an approval process for sales orders that exceed a specific amount.

**Steps**:

1. **Open Odoo Studio**:
   - Go to the **Sales** app.
   - Open **Odoo Studio** by clicking on the Studio icon.

2. **Create a New Workflow Automation**:
   - In the Studio, go to the **Automations** section.
   - Click **Create** to add a new automation.

3. **Define the Trigger**:
   - Set the **Trigger** to "On Sales Order Confirmation."
   - Add a condition: If the total amount of the sales order is greater than a specified amount (e.g., $10,000).

4. **Add an Approval Action**:
   - Set the **Action** to change the sales order status to **Pending Approval**.
   - Optionally, configure an email notification to notify the manager when an order is awaiting approval.

5. **Add Approval Button**:
   - Add a custom button in Studio for the sales manager to approve or reject the sales order.
   - Go to the **Sales Order** form in Studio, and drag a **Button** widget onto the form.
   - Configure the button to change the status to "Approved" or "Rejected."

6. **Test the Workflow**:
   - Exit Studio and create a test Sales Order with a value above the specified amount.
   - Confirm the sales order and observe the workflow in action.

**Result**: The system will automatically flag high-value orders for approval, ensuring they go through the correct review process.

---

### **Module 4: Creating Reports and Dashboards Without Code**

#### **Objective**: Create a custom sales report and display it on a dashboard.

**Steps**:

1. **Navigate to the Sales Reporting Section**:
   - Go to the **Sales** app.
   - In the top menu, click on **Reporting** > **Sales**.

2. **Set the Filter**:
   - Choose a time range or filter relevant to the report (e.g., Sales for the Last Quarter).

3. **Group Data**:
   - Use the **Group By** option to organize data (e.g., Group by **Product Category** or **Salesperson**).

4. **Save the Report**:
   - Click on the **Favorites** button and select **Save As Favorite**.
   - Give the report a name.

5. **Create a Dashboard**:
   - Go to the **Dashboard** app from the main menu.
   - Click **Add to Dashboard** and select the saved report.

6. **Customize the Dashboard**:
   - Add other widgets, such as total sales, top-selling products, etc.
   - Arrange the widgets to create a visually appealing and informative layout.

**Result**: You now have a custom report and dashboard that provide real-time data for decision-making.

---

### **Module 5: Creating a New No-Code Application in Odoo**

#### **Objective**: Build a simple application using Odoo Studio.

**Steps**:

1. **Create a New Application**:
   - Go to **Odoo Studio** and select **Create App**.
   - Name the app according to your business needs (e.g., **Employee Feedback**).

2. **Define the Model**:
   - Create a new model to store the relevant data (e.g., **Feedback**).
   - Add fields like **Employee Name**, **Feedback Type**, **Comments**, and **Rating**.

3. **Customize the Form View**:
   - Use the drag-and-drop interface to design the form, adding the fields where necessary.

4. **Create a Menu**:
   - In Studio, go to the **Menus** section.
   - Create a new menu under an appropriate module (e.g., **Human Resources**).

5. **Add Actions**:
   - Create actions, such as a button to mark feedback as reviewed or to export data.

6. **Test the Application**:
   - Exit Studio and navigate to your new app from the menu.
   - Create a sample record to ensure everything functions as expected.

**Result**: Your custom application is now ready to use, offering functionality tailored to your business process.

---

### **Module 6: Managing Security and Access Control**

#### **Objective**: Implement role-based access control to ensure that users only have access to the information they need.

**Steps**:

1. **Create User Groups**:
   - Go to **Settings** > **Users & Companies** > **Groups**.
   - Create appropriate groups (e.g., **Sales Managers** and **Sales Reps**).

2. **Set Access Rights for Each Group**:
   - For the **Sales Managers** group, grant full access to the Sales module.
   - For the **Sales Reps** group, restrict access to only allow viewing their own records.

3. **Set Up Record Rules**:
   - Go to **Settings** > **Technical** > **Security** > **Record Rules**.
   - Create a record rule for **Sales Reps** to ensure they can only see their own records (e.g., only allow access to records where **Salesperson** = **Current User**).

4. **Assign Users to Groups**:
   - Go to **Settings** > **Users** and assign the relevant users to their respective groups.

5. **Test Access Control**:
   - Log in as a user from each group to verify that the access rights and record rules are applied correctly.

**Result**: Your access control ensures that sensitive data is protected, and users only have access to the records they need for their role.

---

### **Conclusion**

This training provides no-code developers with the tools and knowledge they need to customize Odoo, create reports, automate workflows, and manage security. Using Odoo Studio, you'll be able to tailor the system to fit your organization's unique needs without writing any code.
