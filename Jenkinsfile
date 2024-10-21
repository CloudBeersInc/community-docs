sleep 10
node {
  checkout scm
  isUnix() ? sh('ls -l') : bat('dir')
}
sleep 5
