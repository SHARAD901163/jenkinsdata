node 
{

    checkout scm

    docker.withRegistry('https:hub.docker.com', 'dockerHub') 
      {
        def customImage = docker.build("sp901163/dockapp")
        customImage.push()
      }
}
