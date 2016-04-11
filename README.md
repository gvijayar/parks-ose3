oc new-project [project-name] --description="[project-description]" --display-name="[project-display-name]"
<br />
oc create -f https://raw.githubusercontent.com/gvijayar/parks-ose3/master/parks-ose3-template.json
<br />
oc new-app jws3-tomcat8-postgresql-custom-s2i -p DB_MIN_POOL_SIZE=10,DB_MAX_POOL_SIZE=20
