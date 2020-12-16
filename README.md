# classes-and-module-python

class keyboard:
     def __init__(self,interface, Total of keys, Power consumption, Keystrokes life, net Weight):
         self.Total of keys = Total of keys
         self.Power consumption = Power consumption
         self.Keystrokes life = Keystrokes life
         self.net Weight = Net Weight
         self.interface = interface
         

        
     def display(self):
         print('interface=', self.interface)
         print('Total no. of keys=', self.Total of keys)
         print('Keystrokes life=', self.Keystrokes life)
         print('net Weight=', self.net Weight)
         print('Power consumption=', self.Power consumption )
