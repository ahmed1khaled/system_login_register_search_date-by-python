# system_login_register_search_date-by-python
## This is a fundraising system
# by this function you can register or login with accepted data + you can search by date

# def task():
    print('to register enter 1 /// to login enter 2 /// to search by start date enter 3')
    num1=int(input("enter what is you want : "))
    if num1==1:
        register()
    if num1==2:
        login()
    elif num1==3:
        search_date()
 
  task()
