- review PWG docs and any other related PM docs




- what do I want to focus on as anchor?
- create/maintain a map of priorities for our team / for our problem space
  - who is focused on each of these?
- create a matrix of bbl support
  - should we maintain and/or advertise this?
- talk to Evan about the terraforming repos
  - what are our contracts?
  - testing?
- talk to Evan about our responsibility for consul and etcd, and any related timelines
- lite + jumpbox seems silly
- pm
  - subbing for Evan
  - how else could I help CF without permanently transitioning roles
  - could I have some sort of hybrid role?
    - what does Dmitry's job look like?



- look into bbl state repo
  - targeting by downloading and untarring is annoying
  - is a big download
- create vim shortcut to close test split (from `,t`)
- should the envs just match the job name?
  - I think I was thinking about the "downstream" envs
- investigate our testing
  - terraforming-\*
  - upgrades
  - opsman/releng
  - x-team concerns
- consider providing better feedback when someone forgets to clean up gcp dns
  - do we really need reentrance in `ci/scripts/common/manage-gcp-dns`?
- look into go linters
  - specifically, ignored return values should be made explicit with `_`
- look into / ask about the `bbl-docs-test` pipeline
  - it red af
- is there anything blocking us from getting off wings?
- provide options to `install.sh` in `infrastructure-workspace`
  - e.g. terminal colors (gimme that solarized light!)
- clean up `infrastructure-workspace`
  - `rm bash_profile`?
- we should align how we record temporal documentation
  - git? tracker? other?
  - what sorts of things should we put in each?
  - what level of fidelity?
- shitty name list
  - should this be a x-team concern?
- prompt wish list
  - last exit status
  - start and stop time of last command
- autobump bosh cli in CI
  - was I talking about the docker images when I wrote this?
- compile a list of things that easily remove "secure by default"
  - for spiking
  - "easy but insecure bbl"?
- could we align on underscore vs hyphen strategy in a satisfying way?





- come up with a little Istio/Envoy talk
  - start just for team
  - is it worth sharing with cf at large? maybe after polishing with Gabe?
- pair w/ Rowan on vSphere stuff





- wireshark
- docker
