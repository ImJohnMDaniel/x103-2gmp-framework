#!groovy
@Library('sfdx-core-ci-lib')
import SfdxProjectBuilder
new SfdxProjectBuilder(this)
                .setScratchOrgDefFile('config/project-scratch-def.json')
                .setSlackNotificationsOff()
                .execute()
