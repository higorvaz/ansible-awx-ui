[![CI](https://github.com/ansible/awx/actions/workflows/ci.yml/badge.svg?branch=devel)](https://github.com/ansible/awx/actions/workflows/ci.yml) [![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-Ansible-yellow.svg)](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html) [![Apache v2 License](https://img.shields.io/badge/license-Apache%202.0-brightgreen.svg)](https://github.com/ansible/awx/blob/devel/LICENSE.md) [![AWX Mailing List](https://img.shields.io/badge/mailing%20list-AWX-orange.svg)](https://groups.google.com/g/awx-project)
[![IRC Chat - #ansible-awx](https://img.shields.io/badge/IRC-%23ansible--awx-blueviolet.svg)](https://libera.chat)

<img src="https://raw.githubusercontent.com/ansible/awx-logos/master/awx/ui/client/assets/logo-login.svg?sanitize=true" width=200 alt="AWX" />

AWX provides a web-based user interface, REST API, and task engine built on top of [Ansible](https://github.com/ansible/ansible). It is one of the upstream projects for [Red Hat Ansible Automation Platform](https://www.ansible.com/products/automation-platform).

To install AWX, as sudo.
 - gh repo clone higorvaz/ansible-awx-ui
 - cd ansible-awx-ui
 - pip3 install awxkit
 - awx --help
 - apt install -y nodejs npm
 - npm install
 - /usr/bin/python3 -m pip install --upgrade pip
 - pip3 install requests
 - pip3 install docker-compose
 - pip3 install sphinx sphinxcontrib-autoprogram
 - apt install python3-ldap
 - pip3 check
 - pip3 install -r requirements/requirements_dev.txt
 - apt install python3-xmlsec
 - PIP_USE_DEPRECATED=legacy-resolver 
 - python3 -m pip install --upgrade pip
 - pip3 install -r requirements/requirements.txt
 - pwgen -N 1 -s 30
  - -- nano inventory
 - apt install docker.io
 - systemctl enable docker
 - apt install curl
 - chmod +x /usr/local/bin/docker-compose
 - docker-compose -version

To learn more about using AWX, and Tower, view the [Tower docs site](http://docs.ansible.com/ansible-tower/index.html).

The AWX Project Frequently Asked Questions can be found [here](https://www.ansible.com/awx-project-faq).

The AWX logos and branding assets are covered by [our trademark guidelines](https://github.com/ansible/awx-logos/blob/master/TRADEMARKS.md).

Contributing
------------

- Refer to the [Contributing guide](./CONTRIBUTING.md) to get started developing, testing, and building AWX.
- All code submissions are made through pull requests against the `devel` branch.
- All contributors must use git commit --signoff for any commit to be merged and agree that usage of --signoff constitutes agreement with the terms of [DCO 1.1](./DCO_1_1.md)
- Take care to make sure no merge commits are in the submission, and use `git rebase` vs. `git merge` for this reason.
- If submitting a large code change, it's a good idea to join the `#ansible-awx` channel on web.libera.chat and talk about what you would like to do or add first. This not only helps everyone know what's going on, but it also helps save time and effort if the community decides some changes are needed.

Reporting Issues
----------------

If you're experiencing a problem that you feel is a bug in AWX or have ideas for improving AWX, we encourage you to open an issue and share your feedback. But before opening a new issue, we ask that you please take a look at our [Issues guide](./ISSUES.md).

Code of Conduct
---------------

We ask all of our community members and contributors to adhere to the [Ansible code of conduct](http://docs.ansible.com/ansible/latest/community/code_of_conduct.html). If you have questions or need assistance, please reach out to our community team at [codeofconduct@ansible.com](mailto:codeofconduct@ansible.com)   

Get Involved
------------

We welcome your feedback and ideas. Here's how to reach us with feedback and questions:

- Join the `#ansible-awx` channel on irc.libera.chat
- Join the [mailing list](https://groups.google.com/forum/#!forum/awx-project) 
