Docker Container manager.


### Installing

Install via NPM
* `npm install --global UsabilityDynamics/node-rabbit-manager`

Install via Shell
* `sh <(curl -s http://api.rabbit.ci/install/agent)`
* `sh <(curl -s http://api.rabbit.ci/install/daemon)`
* `sh <(curl -s http://api.rabbit.ci/install/manager)`

### Usage
* rabbit-manager start    [app] - Start service(s).
* rabbit-manager status   [app] - Get status of running services within container.
* rabbit-manager stop     [app] - Stop all running services
* rabbit-manager watch    [dir] - Watch a directory/file/collection for changes and emit changes to AMQP.
* rabbit-manager run      [bin] - Run arbitrary command.
* rabbit-manager reload   [app] - Gracefully reload service, send result to AMQP.
* rabbit-manager install  [app] - Checkout codebase form GitHub and build a Node.js/Composer application, build application and send result to AMQP.
