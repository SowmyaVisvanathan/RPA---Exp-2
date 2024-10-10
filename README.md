### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 2 - Welcome message in Message box with IF Condition

## Aim:
To display a simple welcome message in Message box with IF Condition using UiPath. Get input of name from user and if name is "RAM", Display message as "Welcome back Ram" otherwise "Welcome new user " followed by given name.

## Software required:
UiPath Studio-community edition

## Procedure:

#### **1. Create a New Project in UiPath Studio**
- **Step 1:** Open UiPath Studio Community Edition.
- **Step 2:** Select **"Process"** under the **New Project** section.
- **Step 3:** Name the project, e.g., **"WelcomeUserAutomation"**.
- **Step 4:** Choose a save location and provide a description if necessary.
- **Step 5:** Click **Create** to generate the project.

#### **2. Open the Main Workflow**
- The **Main.xaml** workflow should open by default. If not, double-click it in the **Project Panel** to open it.

#### **3. Add a Sequence Activity**
- **Step 1:** In the **Activities Panel**, search for **"Sequence"**.
- **Step 2:** Drag and drop the **Sequence** activity onto the design canvas.

#### **4. Add an Input Dialog for User Input**
- **Step 1:** In the **Activities Panel**, search for **"Input Dialog"**.
- **Step 2:** Drag and drop the **Input Dialog** activity into the sequence.
- **Step 3:** Configure the **Input Dialog** as follows:
  - **Dialog Title:** `"Input"`
  - **Input Label:** `string.Format("Enter username:")`
  - **Input Type:** `Text Box`
  - **Value:** Create a variable named **`username`** to store the input (set the variable type to String).

#### **5. Add a Log Message Activity**
- **Step 1:** In the **Activities Panel**, search for **"Log Message"**.
- **Step 2:** Drag and drop the **Log Message** activity below the **Input Dialog**.
- **Step 3:** Set the **Message** to: username:
- **Step 4:** Set the **Log Level** to **Trace**.

#### **6. Add an If Activity for Conditional Logic**
- **Step 1:** In the **Activities Panel**, search for **"If"**.
- **Step 2:** Drag and drop the **If** activity below the **Log Message**.

#### **7. Add Message Boxes for Each Scenario**
- **Step 1:** In the **Then** branch of the **If** activity:
  - Drag and drop a **Message Box** activity.
    
- **Step 2:** In the **Else** branch of the **If** activity:
  - Drag and drop a **Message Box** activity.
      
#### **8. Save and Run the Workflow**
- **Step 1:** Click **File** > **Save** to ensure all changes are saved.
- **Step 2:** Click the **Run** button at the top of UiPath Studio to execute the workflow.

## Main.xaml:

![Screenshot 2024-10-08 191705](https://github.com/user-attachments/assets/1b07d154-f328-49ce-933c-7e77bab71aad)


## Output:

![Screenshot 2024-10-08 191751](https://github.com/user-attachments/assets/377824aa-8ce3-4358-b67c-69264e1436b7)

![Screenshot 2024-10-08 191842](https://github.com/user-attachments/assets/93734d5f-a78c-415b-8c68-1efe237337cc)



## Result:
Hence a welcome message in Message box with IF Condition is displayed.


