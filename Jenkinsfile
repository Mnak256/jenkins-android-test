def pipeline = new AndroidPipeline()
stage('build') {
    pipeline.build()
}
stage('post build') {
    pipeline.notify('to be run on device')
}
