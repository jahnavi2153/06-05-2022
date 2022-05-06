# 06-05-2022
'''prepare dictionary for student with the field 
sno,sname,gender,group,result
'''
a={1:[1,'Vedanjali','F','BCA','Pass'],
2:[2,'Mahalaxmi','F','MPC','Pass'],
3:[3,'Deepak','M','BBA','Pass'],
4:[4,'Akhila','F','MECS','Fail'],
5:[5,'Pavan','M','MECS','Fail']}
x=int(input('Enter a number:'))
print('Enter student number:',a[x][0])
print('Enter student name:',a[x][1])
print('Gender:',a[x][2])
print('Group:',a[x][3])
print('Grarde',a[x][4])


output:
Enter a number:4
Enter student number:4
Enter student name:Akhila
Gender:F
Group:MECS
Grade:Fail
