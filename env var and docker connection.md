ENVIRONMENT VARIABLE



\-e ME\_CONFIG\_MONGODB\_SERVER=mongo

\-e ME\_CONFIG\_MONGODB\_ADMINUSERNAME=adminuser 

\-e ME\_CONFIG\_MONGODB\_ADMINPASSWORD=strongpass123 

\-e ME\_CONFIG\_BASICAUTH\_USERNAME=admin 

\-e ME\_CONFIG\_BASICAUTH\_PASSWORD=admin123




**Network**
docker network create mynet



**mongo**
docker run -d -p 27017:27017 --network mynet --name mongo mongo



**express**

docker run -d -p 8081:8081 --network mynet --name mongo-express -e ME\_CONFIG\_MONGODB\_SERVER=mongo -e ME\_CONFIG\_BASICAUTH\_USERNAME=Ragnar -e ME\_CONFIG\_BASICAUTH\_PASSWORD=proniga mongo-express

-------------------------------------------------------------------------------------------------------------------------
FUCKER driver insaller cunt 
systeminfo | findstr /B /C:"System Model"

---------------------------------------------------------------------------------------------------------------------------

**DOCKER** 

**Starting docker images with docker compse yml in the ide** 

configure three files:

docker compse yml
application..yml
and docker file 

create a dokcer connection from for ur ide that 
u can use file setting 

build,execution,deployment --> docker





**connecting BACKEND to DOCKER** 