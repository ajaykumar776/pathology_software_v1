# Objective
# this unix code soln  here 
<!-- The application That I have made Pathology Software. My Objective was To Make This Application Generate reports for patients. The Features That I have Give Admin login, Add Patient in Add patient I have generated a unique Id for each patient. Manage Patients, Generate Reports, *user Side: On the user Side, the User can log in With report Id and mobile no, and there the user can able to see the status of the report either it is pending or successful. from their success report, users can print. -->

<!-- # Technologies Used
* Frontend: HTML, CSS, Boostrap 4,javascript
* Backend: PHP,
# DATABASE DESIGN
![ER  Diagram](snapshots/D.png)
# viedo of working features 
[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://youtu.be/DrWOjiVNeiI)

# snapshots
welcome Page
![welcome Page](snapshots/admin_1.png)
Admin button
![Login page](snapshots/admin_2.png)
login page
![login Page](snapshots/admin_3.png)
login form
![welcome Page](snapshots/admin_4.png)
Dashboard page
![welcome Page](snapshots/admin_5.png)
patient Register
![welcome Page](snapshots/admin_6.png)
Add New Patient form
![welcome Page](snapshots/admin_7.png)
patient Added successfully message
![welcome Page](snapshots/admin_8.png)
Mangage Patient
![welcome Page](snapshots/admin_9.png)
manage patient dashboard
![welcome Page](snapshots/admin_10.png)
Add report
![welcome Page](snapshots/admin_11.png)
add Report page
![welcome Page](snapshots/admin_12.png)
message of successfully added
![welcome Page](snapshots/admin_13.png)
View or report
![welcome Page](snapshots/admin_14.png)
![welcome Page](snapshots/admin_15.png)
![welcome Page](snapshots/admin_16.png)
Click print
![welcome Page](snapshots/admin_17.png)

# userside
welcome page
![welcome Page](snapshots/user_1.png)
login form
![wecome page](snapshots/admin_4.png)
if the user entered wrong password 
![welcome Page](snapshots/1.png)
if the report is pending staus 
![welcome Page](snapshots/2.png)
Success Report  status 
![welcome Page](snapshots/user_7.png)
view report
![welcome Page](snapshots/3.png)
![welcome Page](snapshots/user_10.png)
print
![welcome Page](snapshots/user_11.png) -->
1.
![clear
echo "enter a string"
read a
len=`echo $a | wc -c`
len=`expr $len - 1`
echo "length of the string is $len"

2.
![clear
echo "Enter the year"
read y
if [ `expr $y % 4` -eq 0 ]
then
echo "The given year is a leap year"
else
echo "The given year is not a leap year"
fi]

3.

![clear
echo "enter the number"
read a
if [ `expr $a % 2` -eq 0 ]
then
echo "The given number is even number"
else
echo "The given number is odd number"
fi]


4.

![echo "Enter a number: "
read num
i=2
res=1
if [ $num -ge 2 ]
then
while [ $i -le $num ]
do
res=`expr $res \* $i`
i=`expr $i + 1`
done
fi
echo "Factorial of $num = $res"]


5.

[!clear
echo "enter a string"
read str
len=`echo $str | wc -c`
len=`expr $len - 1`
i=$len
echo "the reverse of the string is"
while [ $len -gt 0 ]
do
ch=`echo $str | cut -c $i`
echo "$ch"
len=`expr $len - 1`
i=`expr $i - 1`
done]

6.
![clear
echo "enter a string"
read str
len=`echo $str | wc -c`
len=`expr $len - 1`
count=0
while [ $len -gt 0 ]
do
ch=`echo $str | cut -c $len`
case $ch in
[aeiouAEIOU] )
count=`expr $count + 1`
echo $ch
;;
esac
len=`expr $len - 1`
done
echo "total vowel is $count"
]
