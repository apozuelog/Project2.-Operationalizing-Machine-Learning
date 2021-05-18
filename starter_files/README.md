# Project2.-Operationalizing-Machine-Learning

This 2nd project is part of Udacity's Nanodegre Machine Learning Engineer with Microsoft Azure.  
Basically it is about working with the dataset provided by Banking Marketing as a dataset and using Azure, and more specifically Azure ML to configure a machine learning model and implement it, also creating an endpoint and a pipeline.  

## Architectural Diagram
As you can see in the architecture figure, the project consists of 7 main milestones (I included one more, swagger) that are described in the following **Key Steps**:  
![logo](IMG/architectur.png)  

## Key Steps

**1. Authentication**  
   Para que el sistema de entrega e integración continua (CI / CD) no se interrumpa, es necesario configurar y usar la autenticación con automatización. Para ello una opción es hacerlo a través de la CLI instalando la extensión ```azure-cli-ml```. Una vez comprobado que tenemos las librerías de Azure ML listas para trabajar con ellas a través de la consola, debemos realizar las siguientes comprobaciones/acciones:  
   ![authentication](IMG/insuficient_privileges.png)  
   En esta imagen se ve como el usuario no tiene privilegios suficientes para realizar la acción.

**2. Automated ML Experiment**  
   Registered Dataset  
   ![authentication](IMG/dataset.png)  
   
   Experiment and best model 
   ![best_model](IMG/experiment_completede_and_best_model.png)  
   
**3. Deploy the best model**  
   Deploy best model, enabled "Authentication" and use Azure Container Instance (ACI)  
   ![deploy](IMG/deplo_best_model_ACI_and_enable_authentication.png)  

**4. Enable logging**  
   ![enable](IMG/insight_enabled_true.png) 

**5. Swagger Documentation**  
   Log.py registered  
   ![log_py](IMG/log_py_register.png) 
   
   Docker swagger  
   ![swagger](IMG/swagger.png)  
   
   ![swagger](IMG/swagger2.png)  

**6. Consume model endpoints**  
   Endpoint  
   ![endpoint](IMG/endpoint.png)  

**7. Create and publish a pipeline**  
   Pipeline  
   ![pipeline](IMG/pipeline.png)  

**8. Documentation**  

## Screen Recording
### Authentication


## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
