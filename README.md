# Silence
Silence is another Content Blocker for iOS. It block contents from known ads domains.

## Lists
The blocker list used in the app is based on the following host list:

| List | License |
| ---------------------------- |:-------------:|
| https://adaway.org/hosts.txt | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) |

The host file is converted to blockList.json by a simple [python script](https://gist.github.com/tsekityam/ce64df36f84b2b87851b4b17315291b9) with the following command:

    $ python convertor.py hosts.txt

## License
```
Copyright 2016 Tse Kit Yam

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
