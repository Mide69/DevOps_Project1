# DevOps_Project1
Linux and Bash Script for account management
#Update Ubuntu
Sudo Apt Update

#create employees
getent group
![Screenshot 2025-05-10 160931](https://github.com/user-attachments/assets/08322b0a-f5ec-4ddb-bad3-973c7d353269)

#Displays all users
cat /etc/passwd
![Screenshot 2025-05-10 160956](https://github.com/user-attachments/assets/55e62e0d-b191-422d-971e-931652f1e058)

#creating users
Sudo adduser username
![Screenshot 2025-05-10 160931](https://github.com/user-attachments/assets/c3e05a5b-34c3-4702-aea0-eaf26253a39b)

#creating group
sudo addgroup group_name
![Screenshot 2025-05-10 161719](https://github.com/user-attachments/assets/e9be69bb-24d3-48e3-9121-87a3bef868b2)

#Assigning users to group
![Screenshot 2025-05-10 163627](https://github.com/user-attachments/assets/da11c1e0-f06c-40c8-9ba2-5b613e4cfcde)


2. 
#create parent directory called company
sudo mkdir company

#Go to the main directory
cd ..

#Go into the company's parent directory
cd company

#Create the office directories
sudo mkdir directories
![Screenshot 2025-05-11 172213](https://github.com/user-attachments/assets/fede53b4-93b9-401b-adc1-18a7c53ff949)


#Assign the right group ownership
sudo chown :finance finance_budgets
sudo chown :legal contract_documents
sudo chown :hr employee_data
sudo chown :strategy business_models
sudo chown :strategy business_projections
sudo chown :admin server_configuration_script
sudo chown :ceo company_vision_and_mission_statement

![Screenshot 2025-05-11 180434](https://github.com/user-attachments/assets/0b4759c1-e6f5-407e-847f-c844353ee673)

#Assign the right ownership

olami@Olamide:/company$ sudo chmod 770 finance_budgets/
olami@Olamide:/company$ sudo chmod 770 contract_documents/
olami@Olamide:/company$ sudo chmod 775 employee_data/
olami@Olamide:/company$ sudo chmod 644 business_projectionss/
#olami@Olamide:/company$ sudo chmod 666 comppany_vision_and_mission_statement/
olami@Olamide:/company$

![Screenshot 2025-05-12 121259](https://github.com/user-attachments/assets/611bace3-7bdf-4c3c-8c6d-7e4849a73ee0)

Task 1: Comments
# This script demonstrates basic Bash scripting concepts, including:
# - Comments
# - Echo command
# - Variables and using them
# - Built-in variables
# - Wildcards

Task 2: Echo
# Display a welcome message
echo "Welcome to Day 1 of the Bash Scripting Challenge!"

Task 3: Variables
# Declare and assign values to variables
name="Olamide"
course="Bash Scripting Challenge"
day=1

Task 4: Using Variables
# Declare two numeric variables and print their sum
num1=10
num2=20
sum=$((num1 + num2))
echo "The sum of $num1 and $num2 is $sum"

Task 5: Using Built-in Variables
# Display script name, number of arguments, and current working directory
echo "Script Name: $0"
echo "Number of Arguments: $#"
echo "Current Working Directory: $PWD"

Task 6: Wildcards
# List all .sh files in the current directory
echo "Listing all .sh files in the current directory:"
ls *.sh

![Screenshot 2025-05-10 173154](https://github.com/user-attachments/assets/51f3b7ae-783c-4f91-812f-5b603fe41cf3)


# End of script
