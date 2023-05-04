# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

### Lab notes
![image](./images)
#### Build triggered and completed after adding graddle.yml in .github/workflow
![image](./images/build%20completed.PNG)

#### cluster created on kubernete
![image](./images/cluseter%20created.PNG)

#### Enable Container and Kubnete engine API
![image](./images/enalbing%20container%20registery%20API%20and%20Kubernetes%20Engine%20API.PNG)

#### The API enabled
![image](./images/API%20enabled.PNG)

#### Google Cloud Dashboard
![image](./images/dashboard%20Google%20cloud%20platform.PNG)

#### Enabling IAM API
![image](./images/IAM%20API%20enabled.PNG)

#### Creaating service account
![image](./images/service%20account%20created.PNG)

#### Granting the acesss for kubernete developer and storage admin
![image](./images/granting%20access.PNG)

#### Policy updated
![image](./images/policy%20updated.PNG)

#### Creating JSON key and downloaded the key
![image](./images/Json%20key%20created%20and%20downloaded.PNG)

#### Setting secret for the repo
![image](./images/setting%20up%20repo%20secret.PNG)

#### GKE_SA_KEY generated
![image](./images/GKE_SA_KEY.PNG)

#### Secret for the git hub repo were generated
![image](./images/secret%20for%20github%20repo%20created.PNG)

#### build 2.4 ( after 2.3) Had to do this since I placed some .yml file in wrong folder so I moved them out!!
![image](./images/build%202.4%20(%20after%202.3)%20Had%20to%20do%20this%20since%20I%20placed%20some%20.yml%20file%20in%20wrong%20folder%20so%20I%20moved%20them%20out.PNG)

#### Released 2.4 build
![image](./images/2.4%20released.PNG)

#### Spring gumbal service deployed to kubernete
![image](./images/spring%20gumball%20deployed%20to%20kuber.PNG)

#### Creating ingress
![image](./images/ingress%20creation.PNG)

#### Created ingress
![image](./images/ingress%20created.PNG)

#### Ingress shown in service and ingress tab
![image](./images/ingress%20shown%20in%20services%20and%20ingress%20tab.PNG)

#### Gumball on GKE
![image](./images/gumball%20on%20GKE.PNG)