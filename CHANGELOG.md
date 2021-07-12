## 2.0.0 (July 7, 2021)

NEW RELEASE WITH BREAKING CHANGES [#46](https://github.com/namecheap/terraform-provider-namecheap/issues/46)

ADDITIONS

## 1.5.0 (November 28, 2019)

ADDITIONS

- add support for ALIAS and CAA resource records

IMPROVEMENTS

- namecheap: upgrade terraform to terraform-plugin-sdk v1.3.0
- build: compile with Go 1.12 and 1.13, modernize dist step

## 1.4.0 (August 7, 2019)

ADDITIONS

- Support `terraform import` for `namecheap_record`
    - Example: `terraform import namecheap_record.foo 'foo.domain.tld/A/127.0.0.1'`

## 1.3.0 (May 22, 2019)

UPGRADES

- Upgraded Terraform to `v0.12.0`
    - Please [read the release notes](https://github.com/hashicorp/terraform/releases/tag/v0.12.0)
      and [Terraform upgrade guide](https://www.terraform.io/upgrade-guides/0-12.html)
- Updated various dependencies and the adamdecaf/namecheap library

IMPROVEMENTS

- namecheap: lower max retry attemts and time.Sleep period

BUILD

- build: remove vendor/ directory

## 1.2.0 (February 26, 2019)

IMPROVEMENTS

- Added backoff and retry for namecheap API errors.

## 1.1.1 (December 4, 2018)

BUG FIXES

- Fixed timeout on record create, delete, and
  updates. ([#7](https://github.com/namecheap/terraform-provider-namecheap/issues/7))

## 1.1.0 (June 8, 2018)

ADDITIONS

* Added `namecheap_ns` record ([#3](https://github.com/namecheap/terraform-provider-namecheap/pull/3))

## 1.0.0 (September 26, 2017)

* No changes from 0.1.1; just adjusting
  to [the new version numbering scheme](https://www.hashicorp.com/blog/hashicorp-terraform-provider-versioning/).

## 0.1.1 (June 21, 2017)

NOTES:

Bumping the provider version to get around provider caching issues - still same functionality

## 0.1.0 (June 21, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part
  of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
