        ___             ___ __      __
       /   | __  ______/ (_) /_____/ /
      / /| |/ / / / __  / / __/ __  / 
     / ___ / /_/ / /_/ / / /_/ /_/ /  
    /_/  |_\__,_/\__,_/_/\__/\__,_/   

Best Practice Auditd Configuration

## Idea

The idea of this auditd configuration is to provide a basic configuration that

- works out-of-the-box on all major Linux distributions 
- fits most use cases
- produces a reasonable amount of log data
- covers security relevant activity
- is easy to read (different sections, many comments)

## Sources

The configuration is based on the following sources

Gov.uk auditd rules
https://github.com/gds-operations/puppet-auditd/pull/1

CentOS 7 hardening
https://highon.coffee/blog/security-harden-centos-7/#auditd---audit-daemon

Linux audit repo 
https://github.com/linux-audit/audit-userspace/tree/master/rules

Auditd high performance linux auditing
https://linux-audit.com/tuning-auditd-high-performance-linux-auditing/

### Further rules

Not all of these rules have been included. 

For PCI DSS compliance see: 
https://github.com/linux-audit/audit-userspace/blob/master/rules/30-pci-dss-v31.rules

For NISPOM compliance see:
https://github.com/linux-audit/audit-userspace/blob/master/rules/30-nispom.rules

## Contribution

Please contribute your changes as pull requests
