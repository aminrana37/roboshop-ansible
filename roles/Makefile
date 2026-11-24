default:
	git pull
	ansible-playbook -i $(component)-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=${component} roboshop.yml 

all:
	ansible-playbook -i frontend-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=frontend roboshop.yml 
	ansible-playbook -i mongodb-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=mongodb roboshop.yml
	ansible-playbook -i catalogue-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=catalogue roboshop.yml  
	ansible-playbook -i redis-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=redis roboshop.yml 
	ansible-playbook -i user-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=user roboshop.yml 
	ansible-playbook -i cart-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=cart roboshop.yml
	ansible-playbook -i mysql-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=mysql roboshop.yml  
	ansible-playbook -i shipping-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=shipping roboshop.yml 
	ansible-playbook -i rabbitmq-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=rabbitmq roboshop.yml
	ansible-playbook -i payment-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=payment roboshop.yml
	ansible-playbook -i dispatch-${env}.mdevsecops.online, -e ansible_user=ec2-user -e ansible_password=DevOps321 -e env=${env} -e component=dispatch roboshop.yml 