pipeline {
			agent {
					label {
							label ('slave-1')
					}
			}
			stages {
					stage ('stage-1') {
										steps {
												sleep 10
										}
					}
					stage ('stage-2') {
										steps {
												dir ('/mnt/test') {
												sh 'mkdir github'
												}
										}
					}
			}
}
