https://educacionadistancia.juntadeandalucia.es/centros/almeria/pluginfile.php/793550/mod_resource/content/6/Unidad_3_v6.pdf
pipeline {
agent any
stages {
stage('First Stage’) {
steps {
echo 'Step 1. Hello World' }
}
stage('Second Stage') {
steps {
echo 'Step 2. Second time Hello'
echo 'Step 3. Third time Hello'
}
}
}
}
