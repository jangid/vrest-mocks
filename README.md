vrest-mocks
===========

Ready mocks to be imported into your vREST instance (http://vrest.io/).

Currently available mocks are:-

* OpenStack (Block Storage API v2)

How to Contribute
-----------------

### Adding mocks to openstack-mocks.json

1. Fork this repository
2. Clone to your work area
3. Import the **openstack-mocks.json** file in this project into [Mock Server tab of vREST](http://vrest.io/i/OpenStack/app.html#testmock)
4. Add more APIs refering to [OpenStack API Reference](http://developer.openstack.org/api-ref-blockstorage-v2.html)
5. Export mock and overwrite openstack-mocks.json with the downloaded file
6. Commit, push and make pull request
