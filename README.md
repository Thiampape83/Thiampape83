Imprt panas as pd

Classe BankCustomer:
    """Bank Customer""" 
     def __init__(self, first_name, last_name, acount_balance) :
     Self. first_name = first_name
     Self. last_name = last_name
     Self. acount_balance = account_balance

     def get_full_name(self):
     full_name = f"{self. first_name} {self. last_name} "
     return full_name. title() 

     def get_account_balance(self) :
     return self. Acount_balance

     def add_money(self, money_amount) :
     Self.account_balance = self.account_balance + money_amount
     return self. Account_balance


     if __name__ ='__main' :
         customer = Bankcustomer(first_name="John, 
                                 last_name=" Doe", 
                                account_balance=4200)

         print(customer. Get_acount_balance()) 

         "" "
         $ vulture unused_code. py
         unused_code. py:1: unused importe 'pd' (90% confidence) 
         unused_code. py:10: unused méthode 'get_full_name' (60%confidence)
         unused_code. Py:17: unused méthode 'add_money' (60%confidence)
         """
