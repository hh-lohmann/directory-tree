# ISSUES

## 25kbk35
##### DONE "path" property in output as optional attribute
* smaller outputs (esp. for large dirs)
* "path" is always given by the resulting JSON's `children` "path"

## 25kbk36
##### DONE output property order: "attributes" before "children"
* current "children" before "attributes" lists parent's "attributes" after propably extensive details on children
* no impact for programmatic consumption of JSON output, but for quick human insight
* especially after +#25kbk35 making "path" an optional "attribute"

## 25kbn01
##### DONE "extension" property also for dirs
* currently `case 'extension': break;`
* DONE copying action from files part
* DONE lifting up "ext" handling to apply for both files and dirs

## 25kbq02
##### DONE package.json: name: "@hh.lohmann/"

## 25kbn02
##### IDEA potential performance improvement: only stat when required
* i.e. without (certain) attributes "stat" should be unnecessary
* for large dirs

## 25kbn03
##### IDEA add existing "extensions" filter to cli
* rather a service than a necessity
