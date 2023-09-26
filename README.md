# cdktf-docker-typescript
A simple helloworld with Terraform CDKTF and Typescript

The tutorial is taken from https://developer.hashicorp.com/terraform/tutorials/cdktf/cdktf-install

Compile:
    npm run get           Import/update Terraform providers and modules (you should check-in this directory)
    npm run compile       Compile typescript code to javascript (or "npm run watch")
    npm run watch         Watch for changes and compile typescript in the background
    npm run build         Compile typescript

  Synthesize:
    cdktf synth [stack]   Synthesize Terraform resources from stacks to cdktf.out/ (ready for 'terraform apply')

  Diff:
    cdktf diff [stack]    Perform a diff (terraform plan) for the given stack

  Deploy:
    cdktf deploy [stack]  Deploy the given stack

  Destroy:
    cdktf destroy [stack] Destroy the stack

  Test:
    npm run test        Runs unit tests (edit __tests__/main-test.ts to add your own tests)
    npm run test:watch  Watches the tests and reruns them on change

  Upgrades:
    npm run upgrade        Upgrade cdktf modules to latest version
    npm run upgrade:next   Upgrade cdktf modules to latest "@next" version (last commit)
