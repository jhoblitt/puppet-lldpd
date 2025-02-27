# Reference

<!-- DO NOT EDIT: This document was generated by Puppet Strings -->

## Table of Contents

### Classes

* [`lldpd`](#lldpd): A module to manage lldpd and related facts

## Classes

### <a name="lldpd"></a>`lldpd`

lldpd

#### Examples

##### Basic usage

```puppet
include lldpd
```

#### Parameters

The following parameters are available in the `lldpd` class:

* [`ensure`](#ensure)
* [`manage_service`](#manage_service)
* [`manage_repo`](#manage_repo)
* [`repourl`](#repourl)
* [`apt_key_hash`](#apt_key_hash)

##### <a name="ensure"></a>`ensure`

Data type: `Enum['present', 'absent', 'latest']`

Install or deinstall all related components

Default value: `'present'`

##### <a name="manage_service"></a>`manage_service`

Data type: `Boolean`

Enable or disable the service management

Default value: ``true``

##### <a name="manage_repo"></a>`manage_repo`

Data type: `Boolean`

Enable or disable the repository setup

Default value: ``false``

##### <a name="repourl"></a>`repourl`

Data type: `Optional[String[1]]`

String that completes the url for the upstream repository

Default value: ``undef``

##### <a name="apt_key_hash"></a>`apt_key_hash`

Data type: `String[1]`

the sha256 hashsum for the GPG key file that was used to sign the packages

Default value: `'2e532e3f800b788b0248da86b1cd722e58e9c99413912fd029c20d88d55ebadc'`

