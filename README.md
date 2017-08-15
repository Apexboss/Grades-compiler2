# Grades-compiler2

x = open('C:/Users/WF_Admin/Documents/project file #2.txt', 'r')
x.close()
x = open('C:/Users/WF_Admin/Documents/project file #2.txt', 'r')
c_a1 = 0
exam1 = 0
c_a2 = 0
exam2 = 0
c_a3 = 0
exam3 = 0
c_a4 = 0
exam4 = 0
for line in x:
    if line[0] == '1'and line[3] != '4':
	    b = (line[-3]) + (line[-2])
	    c = int(b)
	    c_a1 = c_a1 + c		
    elif line[3] == '4'and line[0] == '1':
        d = (line[-3]) + (line[-2])
        e = int(d)
        exam1 = e

x.close()        
x = open('C:/Users/WF_Admin/Documents/project file #2.txt', 'r')
        
for line in x:		
    if line[0] == '2'and line[3] != '4':
        f = (line[-3]) + (line[-2])
        g = int(f)
        c_a2 = c_a2 + g		
    elif line[3] == '4' and line[0] == '2':
        h = (line[-3]) + (line[-2])
        i = int(h)
        exam2 = i

x.close()        
x = open('C:/Users/WF_Admin/Documents/project file #2.txt', 'r')
        
for line in x:		
    if line[0] == '3'and line[3] != '4':
        y = (line[-3]) + (line[-2])
        t = int(y)
        c_a3 = c_a3 + t		
    elif line[3] == '4' and line[0] == '3':
        a1 = (line[-3]) + (line[-2])
        b1 = int(a1)
        exam3 = b1
x.close()        
x = open('C:/Users/WF_Admin/Documents/project file #2.txt', 'r')
        
for line in x:		
    if line[0] == '4'and line[3] != '4':
        a2 = (line[-3]) + (line[-2])
        b2 = int(a2)
        c_a4 = c_a4 + b2		
    elif line[3] == '4' and line[0] == '4':
        a3 = (line[-2]) + (line[-1])
        b3 = int(a3)
        exam4 = b3 
score1 = c_a1 + exam1
score2 = c_a2 + exam2
score3 = c_a3 + exam3
score4 = c_a4 + exam4    
        

print('Subject  ','|','CA','|','Exam','|','Score')
print('-----------------------------')
print('English  ','|',c_a1,'|',exam1,' ','|',score1)
print('-----------------------------')
print('Maths    ','|',c_a2,'|',exam2,' ','|',score2)
print('-----------------------------')
print('Physics  ','|',c_a3,'|',exam3,' ','|',score3)
print('-----------------------------')
print('Chemistry','|',c_a4,'|',exam4,' ','|',score4)
print('-----------------------------')        
