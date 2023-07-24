# Resources to learn more about Packer

## Docker Tutorial

1. Build an Image

* [Packer Builders](https://developer.hashicorp.com/packer/docs/builders) documentation page.
* Source blocks use [builders](https://developer.hashicorp.com/packer/docs/builders) and [communicators](https://developer.hashicorp.com/packer/docs/communicators)
* Read more about the [Docker builder block](https://developer.hashicorp.com/packer/plugins/builders/docker).
* Learn more about the [packer init](https://developer.hashicorp.com/packer/docs/commands/init) and [packer build](https://developer.hashicorp.com/packer/docs/commands/build) commands.
* For more information about Packer-specific HCL blocks, refer to the [Packer HCL](https://developer.hashicorp.com/packer/docs/templates/hcl_templates) documentation page.

2. Provision

* The [shell provisioner](https://developer.hashicorp.com/packer/docs/provisioners/shell)
* Read more about the [Packer provisioners](https://developer.hashicorp.com/packer/docs/provisioners).
* Learn more about how to use [Packer provisioner blocks](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/blocks/build/provisioner).

3. Variables

* There are multiple ways to [assign variables](https://developer.hashicorp.com/packer/guides/hcl/variables#assigning-variables)
* Read more about the [Packer variables](https://developer.hashicorp.com/packer/guides/hcl/variables).
* Learn more about how to use [Packer variable blocks](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/blocks/variable).

4. Parallel Builds

* [Software appliances](https://en.wikipedia.org/wiki/software_appliance)
* Learn how to restrict provisioners to certain build sources with the [`only` and `except` attributes](https://developer.hashicorp.com/packer/docs/templates/hcl_templates/onlyexcept)

5. Post-Processors

* Post-processors are extremely varied in their function; they can [compress](https://developer.hashicorp.com/packer/docs/post-processors/compress) your artifact, [upload](https://developer.hashicorp.com/packer/plugins/post-processors/amazon) your artifact into a cloud, or [create a file](https://developer.hashicorp.com/packer/docs/post-processors/manifest)
* [docker-tag](https://developer.hashicorp.com/packer/plugins/post-processors/docker/docker-tag) post-processor
* If you would like to learn how to use Packer to build Amazon images, check out our [Get Started - Amazon](https://developer.hashicorp.com/packer/tutorials/aws-get-started) tutorials.
* [Packer documentation](https://developer.hashicorp.com/packer/docs)
* [Packer community forum](https://www.packer.io/community)
* Packer is [open source](https://github.com/hashicorp/packer)
