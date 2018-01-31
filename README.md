# -external_dag_run_sensor_plugin
Airflow Dag Run Sensor Plugin


SETUP STEPS TO DEPLOY PLUGIN FILE:
                
                Airflow facilitates users to integrate external features to its core by simply dropping files to {AIRFLOW_HOME}/plugins Directory. To Deploy the ExternalDagRunSensor Plugin follow the steps.
                    a. Create the plugins folder if it doesn't exist.
                         The location you should put it is usually at {AIRFLOW_HOME}/plugins. The specific location can be found in your airflow.cfg file:
                         plugins_folder = /home/{USER_NAME}/airflow/plugins  
                    b. Copy the contents of the plugins folder from this repo into the plugins folder you created on the Airflow server.
                    c. Restart Airflow Services.
