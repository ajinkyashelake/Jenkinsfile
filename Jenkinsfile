pipeline {

agent any

	stages {

		stage ('copy-index') {

			staps {
				sh 'cp -r index.html /var/www/html'


			}


		
		}
		stage ('copy-dev') {

			staps {
				sh 'cp -r dev.html /var/www/html'


			}


		}
		stage ('copy-qa') {

			staps {
				sh 'cp -r qa.html /var/www/html'


			}


		}
		stage ('apache-restart') {

			staps {
				sh 'service httpd start'


			}


		}
	}
}
