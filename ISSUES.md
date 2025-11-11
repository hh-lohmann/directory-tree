# ISSUES

## 25kbk35
##### DONE "path" property in output as optional attribute
* smaller outputs (esp. for large dirs)
* "path" is always given by the resulting JSON's `children` "path"

## 25kbk36
##### TODO output property order: "attributes" before "children"
* current "children" before "attributes" lists parent's "attributes" after propably extensive details on children
* no impact for programmatic consumption of JSON output, but for quick human insight
* especially after +#25kbk35 making "path" an optional "attribute"

## 25kbn01
##### TODO "extension" property also for dirs
* currently `case 'extension': break;`

## 25kbn02
##### IDEA potentila performance improvement: only stat when required
* i.e. without (certain) attributes "stat" should be unnecessary
* for large dirs
