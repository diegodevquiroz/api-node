@Library('company-ci-lib@v1') _

companyPipeline(
    applicationType: 'nodejs',
    environment: 'dev',
    containerImages: [
        node: 'node:20-alpine',
    ],
    stages: [
        'checkout',
        'build-node',
        'unit-test'
    ]
)
