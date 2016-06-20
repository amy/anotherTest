Behance\NBD\Gatekeeper\Gatekeeper
===============






* Class name: Gatekeeper
* Namespace: Behance\NBD\Gatekeeper





Properties
----------


### $_ruleset_provider

```
private \Behance\NBD\Gatekeeper\RulesetProviderInterfaceTESTTESTTEST4 $_ruleset_provider
```





* Visibility: **private**


Methods
-------


### \Behance\NBD\Gatekeeper\Gatekeeper::__construct()

```
mixed Behance\NBD\Gatekeeper\Gatekeeper::\Behance\NBD\Gatekeeper\Gatekeeper::__construct()(\Behance\NBD\Gatekeeper\RulesetProviderInterface $ruleset_provider)
```





* Visibility: **public**

#### Arguments

* $ruleset_provider **Behance\NBD\Gatekeeper\RulesetProviderInterface**



### \Behance\NBD\Gatekeeper\Gatekeeper::canAccess()

```
boolean Behance\NBD\Gatekeeper\Gatekeeper::\Behance\NBD\Gatekeeper\Gatekeeper::canAccess()(string $feature, string|array|null $identifier)
```





* Visibility: **public**

#### Arguments

* $feature **string**
* $identifier **string|array|null**



### \Behance\NBD\Gatekeeper\Gatekeeper::getActiveFeatures()

```
array Behance\NBD\Gatekeeper\Gatekeeper::\Behance\NBD\Gatekeeper\Gatekeeper::getActiveFeatures()(string|array|null $identifier)
```





* Visibility: **public**

#### Arguments

* $identifier **string|array|null**



### \Behance\NBD\Gatekeeper\Gatekeeper::getPercentageFeaturesByActiveState()

```
array Behance\NBD\Gatekeeper\Gatekeeper::\Behance\NBD\Gatekeeper\Gatekeeper::getPercentageFeaturesByActiveState()(string|array|null $identifier)
```





* Visibility: **public**

#### Arguments

* $identifier **string|array|null**



### \Behance\NBD\Gatekeeper\Gatekeeper::_getRuleTypeFeaturesByActiveState()

```
array Behance\NBD\Gatekeeper\Gatekeeper::\Behance\NBD\Gatekeeper\Gatekeeper::_getRuleTypeFeaturesByActiveState()(string $rule_type, string|array|null $identifier)
```





* Visibility: **private**

#### Arguments

* $rule_type **string**
* $identifier **string|array|null**


