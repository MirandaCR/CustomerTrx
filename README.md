# **CustomerTrx**  

### **Descripción**  
Este proyecto de ingeniería de datos consiste en la ingesta de datos con Python a PostgresSQL de tres tablas: una tabla de transacciones de ventas de bicicletas, una tabla de clientes y una tabla de direcciones de donde viven los clientes en Australia. El objetivo del proyecto es poder analizar las transacciones de ventas de bicicletas y los patrones de comportamiento de los clientes en Australia a través de la creación de un Dahboard en Power BI.  

### **Datos**  
Los datos para este proyecto fueron extraidos de Kaggle y consideran las  [**Transacciones de clientes**](https://www.kaggle.com/datasets/archit9406/customer-transaction-dataset) que compraron accesorios de bicicletas en Australia en 2017. 

Existen 3 tablas distintas que son:
- Demografía de clientes
- Direcciones de clientes
- Datos de transacciones en los últimos 3 meses.


### **Ingeniería de Datos**  

Para comprender de mejor manera el flujo de trabajo de la ingeniería de datos se presenta el siguiente diagrama que muestra cada uno de los pasos dpor los que pasan los datos:

![flujo](https://github.com/MirandaCR/CustomerTrx/blob/main/Images/ArchitectureData.png)


**Nota:** Antes de generar el traspaso de los datos a PostreSQL con Python se necesita tener instalado y configurado el [**Cliente de PostgreSQL**](https://www.postgresql.org/ftp/odbc/versions/msi/)
  




