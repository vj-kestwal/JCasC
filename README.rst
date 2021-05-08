JCasC
==================

Installation and configuration of Jenkins using Docker and the Jenkins Configuration as Code (JCasC) method.

Pre-Condition
------------------

* Docker should be installed

Docker Build command
------------------

.. code-block:: shell

   docker build -t jenkins:JCasC .


Docker Run command
------------------

.. code-block:: shell

   docker run --name jenkins -d -p 8080:8080 --env JENKINS_ADMIN_ID=admin --env JENKINS_ADMIN_PASSWORD=password jenkins:JCasC


Based on
-----------------

* https://www.digitalocean.com/community/tutorials/how-to-automate-jenkins-setup-with-docker-and-jenkins-configuration-as-code
