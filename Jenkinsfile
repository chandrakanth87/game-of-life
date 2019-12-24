node{
	stage(svn){
	  git credentialsId: '5fe137f5-826f-4e95-8713-0caa58467616', url: 'https://github.com/chandrakanth87/gameoflife.git'
	}
	stage(package){
	  sh 'mvn package'
	}
}
