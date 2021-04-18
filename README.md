class budget:
    def __init__(self,item,brand,amount):
        self.item=item
        self.brand=brand
        self.amount=amount

    def deposit(self):
        print(f'make deposit in {self.item}')
    @classmethod
    def how_much(cls):
        int(input(f'How much would you like to deposit \n'))
        

    def check_balance(self):
        print(f'check balance of {self.item}')
        print('current balance')
    def transfer(self):
        print(f'Make transfer to {self.item}')
    @classmethod
    def transfer_money(cls):
        int(input('How much would you like to transfer \n'))
        
    def withdraw(self):
        print(f'Make withdrawal from {self.item}')
    @classmethod
    def withdrawal(cls):
        int(input('How much would you like to withdrawal \n'))
    
        
        

category1=budget('clothing','gucci',20000)
category2=budget('shoes','nike',5000)
category3=budget('cars','tesla',25000)
category4=budget('phone','samsung',1000)
category5=budget('bags','jansport',2000)

category1.deposit()
category2.deposit()
category3.deposit()
category4.deposit()
category5.deposit()

category1.how_much()
category1.check_balance()
category2.check_balance()
category3.check_balance()
category4.check_balance()
category5.check_balance()

category1.transfer()
category2.transfer()
category3.transfer()
category4.transfer()
category5.transfer()
category1.transfer_money()
category1.withdraw()
category2.withdraw()
category3.withdraw()    
category4.withdraw()
category5.withdraw()
category1.withdrawal()
