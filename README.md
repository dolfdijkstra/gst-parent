gst-parent
==========

Parent pom for GST projects


Notes on how to release to github

mvn release:prepare
mvn -DaltDeploymentRepository=repo::default::file:../../mvn-repository/releases release:perform 
