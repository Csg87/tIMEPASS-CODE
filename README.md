# TIMEPASS-CODE

Stud_Name = input("Please enter your Name: ")
Stud_USN = input("Please enter your USN: ") #1SI18IM007
Stud_Sem = int(input("Please enter your Sem: "))

if Stud_Sem == 1:
    if Stud_USN[-5] == 'I' and Stud_USN[-4] == 'M':
        print("Hi " + str(Stud_Name)+ ", you belong to IEM go to IEM 202 for more info.\n Thank you")
    elif Stud_USN[-5] == 'M' and Stud_USN[-4] == 'E':
        print("Hi " + str(Stud_Name)+ ", you belong to Mech go to ME 202 for more info.\n Thank you")
    elif Stud_USN[-5] == 'C' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to CS go to CS 202 for more info.\n Thank you")
    elif Stud_USN[-5] == 'I' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to IS go to IS 202 for more info.\n Thank you")
    else:
        print("You've entered wrong USN")
elif Stud_Sem == 3:
    if Stud_USN[-5] == 'I' and Stud_USN[-4] == 'M':
        print("Hi " + str(Stud_Name)+ ", you belong to IEM go to IEM 203 for more info.\n Thank you")
    elif Stud_USN[-5] == 'M' and Stud_USN[-4] == 'E':
        print("Hi " + str(Stud_Name)+ ", you belong to Mech go to ME 203 for more info.\n Thank you")
    elif Stud_USN[-5] == 'C' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to CS go to CS 203 for more info.\n Thank you")
    elif Stud_USN[-5] == 'I' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to IS go to IS 203 for more info.\n Thank you")
    else:
        print("You've entered wrong USN")
elif Stud_Sem == 5:
    if Stud_USN[-5] == 'I' and Stud_USN[-4] == 'M':
        print("Hi " + str(Stud_Name)+ ", you belong to IEM go to IEM 204 for more info.\n Thank you")
    elif Stud_USN[-5] == 'M' and Stud_USN[-4] == 'E':
        print("Hi " + str(Stud_Name)+ ", you belong to Mech go to ME 204 for more info.\n Thank you")
    elif Stud_USN[-5] == 'C' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to CS go to CS 204 for more info.\n Thank you")
    elif Stud_USN[-5] == 'I' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to IS go to IS 204 for more info.\n Thank you")
    else:
        print("You've entered wrong USN")
elif Stud_Sem == 7:
    if Stud_USN[-5] == 'I' and Stud_USN[-4] == 'M':
        print("Hi " + str(Stud_Name)+ ", you belong to IEM go to IEM 205 for more info.\n Thank you")
    elif Stud_USN[-5] == 'M' and Stud_USN[-4] == 'E':
        print("Hi " + str(Stud_Name)+ ", you belong to Mech go to ME 205 for more info.\n Thank you")
    elif Stud_USN[-5] == 'C' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to CS go to CS 205 for more info.\n Thank you")
    elif Stud_USN[-5] == 'I' and Stud_USN[-4] == 'S':
        print("Hi " + str(Stud_Name)+ ", you belong to IS go to IS 205 for more info.\n Thank you")
    else:
        print("You've entered wrong USN")
else:
    print("Enter your details properly")
