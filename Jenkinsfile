node { 
  stage('========== Clone repository ==========') { 
    checkout scm 
} 
     stage('Kubernetes deploy') {
        kubernetesDeploy configs: "test.yaml", kubeconfigId: 'kube'
}
    }
