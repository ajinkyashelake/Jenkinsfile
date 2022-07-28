pipeline {

agent any

	stages {

		stage ('copy-index') {

			steps {
				sh 'cp -r index.html /var/www/html/'


			}


		
		}
		stage ('copy-dev') {

			steps {
				sh 'cp -r dev.html /var/www/html/'


			}


		}
		stage ('copy-qa') {

			steps {
				sh 'cp -r qa.html /var/www/html/'


			}


		}
		stage ('apache-restart') {

			steps {
				sh 'service httpd restart'


			}


		}
	}
}
