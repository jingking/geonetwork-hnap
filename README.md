# Helm Charts for GeoNetowrk Deployment
 Helm Charts for GeoNetowrk with Harmonized North American Profile (HNAP) plugin 
 <br>The current version for both GeoNetwork and HNAP is v4.2.7
 <br>Optional sub-charts include postgress-postgis, elasticsearch, kibana, ogc-api-records-service 

## Usage 
If you are running in your local Kubernetes environment, ensure that you have a persistent volume ready. 
<br>Double-check the values.yaml file, paying particular attention to the ingress parameters.
 ````
helm install -n <your namespace> geonetwork ./geonetwork-4.2.7
 ````
