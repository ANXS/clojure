## ANXS - clojure [![Build Status](https://travis-ci.org/ANXS/clojure.png)](https://travis-ci.org/ANXS/clojure)

Ansible role which installs [Clojure](http://clojure.org/) and [leiningen](http://leiningen.org/).


#### Requirements & Dependencies
- Tested on Ansible 1.3 or higher.


#### Variables

```yaml
clojure_versions: ["1.5.1"]             # A list of clojure versions you want to have installed
clojure_default_version: "1.5.1"        # The clojure version you want to be the system default
clojure_leiningen_version: "2.3.4"      # The version of leiningen to install
```


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/clojure/issues)!
