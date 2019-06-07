# Exim4

## Smarthost configuration
Variables for smarthost:

* exim4_is_smarthost boolean, enable to use smarthost config.
* exim4_smarthost_relay_for list of ansible hostnames that are allowed to
  relay.

For smarthost clients:

* exim4_smarthost smarthost domain.
* exim4_use_client_certificates boolean, enable to generate client certificates.
* exim4_configtype should be set to 'satellite' for clients or use the following:
* exim4_partial_smarthost_percentage send only defined percentage of traffic to smarthost.
