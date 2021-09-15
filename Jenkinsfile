node 
{

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') 
      {
        def customImage = docker.build("sp901163/dockapp")
        customImage.push()
      }
}