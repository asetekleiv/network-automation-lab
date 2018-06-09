<!DOCTYPE html>
<html>
<body>

<h2>Description of playbook</h2>

<ol style="list-style-type:circle">
  <li>00_generate_build_deploy_check.yml - complete playbook </li>
  <li>01_create_config_env.yml</li>
  <li>02_fabric2node.yml</li>
  <li>03_generate-config.yml</li>
  <li>04_deploy-infrastructure.yml</li>
  <li>05_test-infrastructure.yml</li>
  <li>06_create-service-validation.yml</li>
  <li>07_services-pretest.yml</li>
  <li>08_services-deploy.yml</li>
  <li>09_services-validation.yml</li>
  <li>10_services-discrepancies_cleanup.yml</li>
  
</ol> 

Run "00_generate_build_deploy_check.yml - complete playbook" for a complete play, will fail on 07 if serviceinterfaces allready exists

</body>
</html>