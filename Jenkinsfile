@Library('OpenSlateProd')_  // https://github.com/openslate/jenkins-shared-library

def publishWhen = { env.TAG_NAME }

openslatePipeline {
    mentions = '<@UB22LFDEJ>'
    deployEnv = 'prod'
    publish = publishWhen
    deploy = false
}
