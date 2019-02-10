# Gobis-boshrelease

A boshrelease to run a [gobis-server](https://github.com/orange-cloudfoundry/gobis-server) in bosh machine.

This let you use gobis as a sidecar in front of other component and add for exemple authentication, 
see [middlewares](https://github.com/orange-cloudfoundry/gobis-server) to know what you can do. 

## Usage

Like this release should be use in front of other job, we can't provide manifest example here.

You can first look at [gobis job spec](/jobs/gobis/spec) to know parameters and see example of usage on 
[terraform-secure-backend-release](https://github.com/orange-cloudfoundry/terraform-secure-backend-release/blob/master/manifests/operators/access-limited-deployment.yml).

**/!\IMPORTANT: gobis job need to have [bpm](https://github.com/cloudfoundry-incubator/bpm-release)** 