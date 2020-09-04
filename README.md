polkadot-validator
=========

This role prepares the node for installation of the Polkadot client as a validator node.

Role Variables
--------------

- project: default
- count: 0
- polkadot_additional_common_flags:
- polkadot_additional_validator_flags:
- loggingFilter: "sync=trace,afg=trace,babe=debug"
- chain: polkadot
- chain_stub: polkadot
- base_path:
- default_telemetry_enabled: false
- telemetryUrl:

Dependencies
------------

- w3f_insight.polkadot_base

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: insight_w3f.polkadot_validator }

License
-------

Apache 2.0

Author Information
------------------

Maintained by [Richard Mah](https://github.com/shinyfoil) for [Insight Infrastructure](https://github.com/insight-infrastructure)
