# Deepmatrix_Docs


<h2>Jenkins installation on GCP</h2>
<a href="https://medium.com/bb-tutorials-and-thoughts/how-to-run-jenkins-on-gcp-vm-29dc18490fae">Link</a>
<h3> Commands </h3>
<ul>
  <li>
  curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
  </li>
  <li>
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
  </li>
  <li>
sudo apt-get update
  </li>
  <li>
sudo apt-get install jenkins
  </li>
 </ul>
</p>

<p>After installing jenkins change the port tag by using edit option….and change it to 8080</p>
<hr>
<h2>Jenkins pipeline build trigger on github push</h2>
<a href="https://blogs.sap.com/2015/12/15/configuring-jenkins-to-run-a-build-automatically-on-code-push/#:~:text=In%20Jenkins%2C%20go%20to%20the,code%20to%20the%20GitHub%20repository"> Link </a>
<p>To open dashboard :(external_IP of instance)/port </p>
</p> eg=>http://35.193.3.249:8080/   </p>

<hr>


<h2>Jenkins Pipeline</h2>

<ul>
  <li>Create a new pipeline</li>
  <li>Add github repo url </li>
  <li> Select GitHub hook trigger for GITScm polling </li>
  <li>Select GIT SCM option ,add url and add the branch </li>
  <li> Add the Jenkinsfile path </li>
</ul>


# quarkus stop pulling 
quarkus.devservices.enabled=false



username: DMadmin
pass: DMadmin123@


Give Docker Sudo permissions
```
groupadd docker
sudo usermod -aG docker $USER
sudo chmod 666 /var/run/docker.sock

```


https://www.javafixing.com/2022/06/fixed-testcontainers-postgres-quarkus.html


https://solocoding.dev/blog/eng_docker_testcontainer



##CONTAINER TEST
1) change exposed port to 5432
2) use docker login docker.index.io to login
3) use netcfg -d then restart
4) change ryuk/testcontainer properties


http://www.mastertheboss.com/soa-cloud/quarkus/simple-external-resources-testing-with-quarkus/


////AVOID using Policy
# Enable Policy Enforcement
quarkus.keycloak.policy-enforcer.enable=true
quarkus.keycloak.policy-enforcer.lazy-load-paths=false

Quarkus_Liquibase
https://capgemini.github.io/development/Quarkus-meets-Liquibase/
https://quarkus.io/guides/liquibase



# Kube jenkins
https://www.jenkins.io/doc/book/installing/kubernetes/#create-a-namespace
