@Library('company-ci-lib@v1') _

companyPipeline(
    applicationType: 'nodejs',
    environment: 'dev',
    containerImages: [
        node: 'node:20-alpine',
    ],
    overrides: [version: '1.0.0'],
    stages: [
        'checkout',
        'build-node',
        'unit-test'
    ]
)
