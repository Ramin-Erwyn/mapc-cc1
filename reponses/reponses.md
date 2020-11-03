 
###### QUESTION2 RAMIN ####
je distingue 5 Design Pattern : 
- **Factory Method** 
- **Composite**
- **Builder**
- **visitor** que nous avons à  fait mais sera utiliser ailleur
- **singleton**

ils sont tous melanger comme une fision de plusieurs pattern 
le factory et le builder et composite et builder avec le visitor

Le Dry nous permets de ne pas nous prépeter c'est grave à la methode de factory pattern 
c'est un methode de nous permets de pas avoir les memes ligne de codes 

| Builder | Factory Method | Visitor | Singleton |
| ------- | -------------- | --------- | --------- |
| DeploymentPlan _(abstract)_ <br> ComputeNode _(concrete)_ <br> VirtualMachine _(concrete)_ <br> Component _(concrete)_ <br> Service _(concrete)_| Component _(concrete)_ <br> Service _(concrete)_| Visitor _(abstract)_ | ServiceDefinitionLoader | 
| ------- | -------------- | --------- | --------- |
| | | | ComponentTypeRegistry |
| ------- | -------------- | --------- | --------- |
| | | | ServiceTypeRegistry |

