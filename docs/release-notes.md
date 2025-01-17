<style>
    .md-typeset h2 {
        font-weight: bold;
    }
</style>


## v5.2.1
August 6, 2024


### Maintenance release

## v5.1.2
June 15, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.27.153 |
    | azure-cli | 2.49.0 |
    | bbr-cli | [1.9.46](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.46) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.16](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.16) |
    | gcloud-cli | 435.0.1 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-5.1.2" target="_blank">Download</a>

### Maintenance Release
- Update Platform Automation Toolkit to use Ubuntu Jammy-based Paketo buildpack images


## v5.1.1
May 5, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.24.10 |
    | azure-cli | 2.39.0 |
    | bbr-cli | [1.9.44](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.44) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.14](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.14) |
    | gcloud-cli | 429.0.0 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-5.1.1" target="_blank">Download</a>

### Bug Fixes
- Update govc to v0.30.4
- Delete all python files from vsphere-only docker image


## v5.1.0
February 27, 2023

??? info "CLI Versions"

     | Name | version |
     |---|---|
     | aws-cli | 1.24.10 |
     | azure-cli | 2.39.0 |
     | bbr-cli | [1.9.38](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.38) |
     | bosh-cli | [v7.1.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.1.3) |
     | credhub | [2.9.11](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.11) |
     | gcloud-cli | 419.0.0 |
     | govc-cli | 0.30.2 |
     | om | 2ba733630d765e1b41e815ce1b49e825da2c192b-2023-02-24T11:33:19-07:00 |
     | winfs-injector | [0.21.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.21.0) |
         
    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-5.1.0" target="_blank">Download</a>

### What's New
- Added new How-to Guide about [Rotating Certificate Authority][rotating-certificate-authority].
  This how-to-guide shows you how to write a pipeline for rotating the certificate authority on an existing Tanzu Operations Manager.
- The following additional tasks have been added to help with rotating certificate authorities:
  * [`activate-certificate-authority`][activate-certificate-authority]
  * [`configure-new-certificate-authority`][configure-new-certificate-authority]
  * [`delete-certificate-authority`][delete-certificate-authority]
  * [`generate-certificate`][generate-certificate]
  * [`regenerate-certificates`][regenerate-certificates]

{% include ".internal_link_url.md" %}
{% include ".external_link_url.md" %}
## v5.0.26
June 25, 2024




## v5.0.25
June 15, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.27.153 |
    | azure-cli | 2.49.0 |
    | bbr-cli | [1.9.46](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.46) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.16](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.16) |
    | gcloud-cli | 435.0.1 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-5.0.25" target="_blank">Download</a>

### Maintenance Release
- Update Platform Automation Toolkit to use Ubuntu Jammy-based Paketo buildpack images


## v5.0.24
May 5, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.24.10 |
    | azure-cli | 2.39.0 |
    | bbr-cli | [1.9.44](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.44) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.14](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.14) |
    | gcloud-cli | 429.0.0 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-5.0.24" target="_blank">Download</a>

### Bug Fixes
- Update govc to v0.30.4
- Delete all python files from vsphere-only docker image


## v4.4.33
June 25, 2024




## v4.4.32
June 15, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.27.153 |
    | azure-cli | 2.49.0 |
    | bbr-cli | [1.9.46](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.46) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.16](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.16) |
    | gcloud-cli | 435.0.1 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-4.4.32" target="_blank">Download</a>

### Maintenance Release
- Update Platform Automation Toolkit to use Ubuntu Jammy-based Paketo buildpack images


## v4.4.31
May 5, 2023

??? info "CLI Versions"

    | Name | version |
    |---|---|
    | aws-cli | 1.24.10 |
    | azure-cli | 2.39.0 |
    | bbr-cli | [1.9.44](https://github.com/cloudfoundry-incubator/bosh-backup-and-restore/releases/tag/v1.9.44) |
    | bosh-cli | [v7.2.3](https://github.com/cloudfoundry/bosh-cli/releases/tag/v7.2.3) |
    | credhub | [2.9.14](https://github.com/cloudfoundry-incubator/credhub-cli/releases/tag/2.9.14) |
    | gcloud-cli | 429.0.0 |
    | govc-cli | 0.30.4 |
    | om | 45876ef5954ddb419cd88126d77b4e8ebb2ca554-2023-05-03T17:38:11-07:00 |
    | winfs-injector | [0.22.0](https://github.com/pivotal-cf/winfs-injector/releases/tag/0.22.0) |

    The full Docker image-receipt: <a href="https://platform-automation-release-candidate.s3-us-west-2.amazonaws.com/image-receipt-4.4.31" target="_blank">Download</a>

### Bug Fixes
- Update govc to v0.30.4
- Delete all python files from vsphere-only docker image

