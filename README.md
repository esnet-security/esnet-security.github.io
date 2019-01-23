# ESnet Security

Announcements and other content from the [ESnet](https://es.net) Security team.

## Announcements

### RSSH Command Execution Vulnerability (CVE-2019-1000018)

The ESnet Security team is [publishing a vulnerability](vulnerabilities/20190115_rssh) in `rssh`. This software is used to restrict SSH access to a system, only allowing a user to `scp` files to/from the system. The vulnerability allows such a user to execute arbitrary code as well. For a detailed write-up of how we discovered this issue, see our [SANS 2018 Holiday Hack report](https://software.es.net/sans-holiday-hack-2018/#org55a074b).

## History

Jan 15, 2019: Published [RSSH vulnerability](vulnerabilities/20190115_rssh).

Jan 14, 2019: Published [SANS Holiday Hack](https://software.es.net/sans-holiday-hack-2018/) report.
