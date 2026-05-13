# PAI-Bolivia
* Descripcion del proyecto *
 Estructura 
Dataset
Modelos (consultas sql para crear el datawarehouse)
Terraform
Videos
 Stack Azure 
Grupo de Recurso
Storage accounts - datalake gen 2
sql database
azure datafactory
 Arquitectura 
Bronze -> datos crudos
Silver -> limpieza e integracion de los datos
gold -> creacion del datawarehouse etl & pipelineas
 Solucion 
*** Metodo 1 ***
bronze -> datalake
silver -> schema silver
gold -> schema gold y datawarehouse
*** Metodo 2 ***
raw -> datalake - datos en brutos
bronze -> schema bronze
silver -> schema silver
gold -> schema gold y datawarehouse
