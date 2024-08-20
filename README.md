# Catalog-Hackathon--3

Pharma Supply Chain System using Smart Contracts:
The pharmaceutical industry faces some challenges related to security and integrity of supply chains.The major concept which is considered in this scenario is about efficient tracking and tracing of drugs in this particular industry.By implementing this technique the efficiency can be improved and the loss of that industry will be reduced.

Benefits of using smart contracts in pharma supply chain:
________________>>>Enhanced Security
--------------- >>>Increasing Efficiency
---------------->>>Reducing Cost

IMPLEMENTION OF CODE OF PHARMA SUPPLY CHAIN SYSTEM:
Steps for implementation--------------->> 1)to manufacture the drug
2)shipping the drug
3)Recieving the drug
4)Tracking the drug

In the mentioned code the total code is divided into classes namely drug class to repesent the individual drug batch,supply chain class and Stimulation class.
class Drug:
      class Drug:
    def __init__(self, batch_number, name, manufacturer):
        self.batch_number =batch_number
        self.name =name
        self.manufacturer =manufacturer
        self.history =[]
        self.add_to_history("Manufactured", manufacturer)


///add to history method is used to add a method to drugs history.
        def add_to_history(self,event,party):
        self.history.append({
            "event":event,
            "party":party
        })
        def get_history(self):
        return self.history                    ------------------to return the history
        class supplychain
        def __int__(self){
        self.drugs={}
}
def man_drug(self,batch_number,name,manufacturer):
    if batch_number in self.drugs{
    printf("The drug with this particular batch number exists")
    else:
     drug=Drug(drug,batch_number,name,manufacturer) {
     self.drug[Batch_number] = drug
     print("Drug{name} batch number{Batch_number} manufacturer{manufacturer}")
def ship_drug(self,batch_number,name,distributor):
   if batch_number in self.drugs{
   self.drug[Batch_number] = drug
   drug.add_to_history("Shipped"{Distributor})
   print(f"{batch_number} shipped by {Distributor})
   else:
   print(f"number not found")
 def receive_drug(self, batch_number, pharmacy):              
        if batch_number in self.drugs:
            drug = self.drugs[batch_number]
            drug.add_to_history("Received",pharmacy)
            print(f"Drug (Batch #{batch_number}) received by {pharmacy}.")
        else:
            print(f"Drug with batch number {batch_number} not found.")
    def dis_drug(self,batch_number,customer):
        if batch_number in self.drugs:
            drug = self.drugs[batch_number]
            drug.add_to_history("Dispensed",customer)
            print(f"Drug(Batch #{batch_number}) dispensed to {customer}.")
        else:
            print(f"Drug with batch number {batch_number} not found.")
    
////track function is used at last to print the entire histoy of drug:
       def track_drug(self,batch_number):
        if batch_number in self.drugs:
            drug = self.drugs[batch_number]
            print(f"Tracking history for Drug (Batch #{batch_number}):")
            for event in drug.get_history():
                print(f" {event['event']} by {event['party']}")
        else:
            print(f"Drug with batch number {batch_number} not found.")
 ////To Stimulate the Pharma supply Chain
       supply_chain=Supply_Chain
       supply_chain.man_dru=(1234,"COVID-19","ABC PHARMA")
       supply_chain.ship_drug(1234,"Sanjana")
       supplychain.recieve_drug1234,"Health Mart Pharmacy")
       suppychain.dis_drug(1234,Sanjana)
       supplychain.track_drug(1234)















  

   




   

   




     











  




        


































