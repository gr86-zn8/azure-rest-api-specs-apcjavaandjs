## Ruby

These settings apply only when `--ruby` is specified on the command line.

``` yaml
package-name: azure_mgmt_event_grid
package-version: "0.16.1"
azure-arm: true
```

### Ruby multi-api

``` yaml $(ruby) && $(multiapi)
batch:
  - tag: package-2025-04-preview
  - tag: package-2025-02
  - tag: package-2024-06-preview
  - tag: package-2023-12-preview
  - tag: package-2023-06-preview
  - tag: package-2022-06
  - tag: package-2021-10-preview
  - tag: package-2021-12
  - tag: package-2021-06-preview
  - tag: package-2020-10-preview
  - tag: package-2020-06
  - tag: package-2020-04-preview
  - tag: package-2020-01-preview
  - tag: package-2019-06
  - tag: package-2019-02-preview
  - tag: package-2019-01
  - tag: package-2018-09-preview
  - tag: package-2018-05-preview
  - tag: package-2018-01
  - tag: package-2017-09-preview
  - tag: package-2017-06-preview
```
### Tag: package-2025-04-preview and ruby
These settings apply only when `--tag=package-2025-04-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2025-04-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2025_04_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2025-02 and ruby
These settings apply only when `--tag=package-2025-02 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2025-02' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2025_02_15"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2024-06-preview and ruby
These settings apply only when `--tag=package-2024-06-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2024-06-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2024_06_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2023-12-preview and ruby
These settings apply only when `--tag=package-2023-12-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2023-12-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2023_12_15_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2023-06-preview and ruby
These settings apply only when `--tag=package-2023-06-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2023-06-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2023_06_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2022-06 and ruby
These settings apply only when `--tag=package-2022-06 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2022-06' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2022_06_15"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2021-10-preview and ruby
These settings apply only when `--tag=package-2021-10-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2021-10-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2021_10_15_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2021-12 and ruby
These settings apply only when `--tag=package-2021-12 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2021-12' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2021_12_01"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2021-06-preview and ruby
These settings apply only when `--tag=package-2021-06-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2021-06-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2021_06_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2020-10-preview and ruby
These settings apply only when `--tag=package-2020-10-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2020-10-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2020_10_15_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```


### Tag: package-2020-06 and ruby
These settings apply only when `--tag=package-2020-06 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2020-06' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2020_06_01"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2020-01-preview and ruby
These settings apply only when `--tag=package-2020-04-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2020-04-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2020_04_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2020-01-preview and ruby
These settings apply only when `--tag=package-2020-01-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2020-01-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2020_01_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2019-06 and ruby
These settings apply only when `--tag=package-2019-06 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2019-06' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2019_06_01"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2019-02-preview and ruby
These settings apply only when `--tag=package-2019-02-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2019-02-preview' && $(ruby)

namespace: "Azure::EventGrid::Mgmt::V2019_02_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2019-01 and ruby

These settings apply only when `--tag=package-2019-01 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2019-01' && $(ruby)
namespace: "Azure::EventGrid::Mgmt::V2019_01_01"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2018-09-preview and ruby 
These settings apply only when `--tag=package-2018-09-preview --ruby` is specified on the command line. 
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`. 

``` yaml $(tag) == 'package-2018-09-preview' && $(ruby) 

namespace: "Azure::EventGrid::Mgmt::V2018_09_15_preview" 
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib 
```

### Tag: package-2018-05-preview and ruby

These settings apply only when `--tag=package-2018-05-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2018-05-preview' && $(ruby)
namespace: "Azure::EventGrid::Mgmt::V2018_05_01_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2018-01 and ruby

These settings apply only when `--tag=package-2018-01 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2018-01' && $(ruby)
namespace: "Azure::EventGrid::Mgmt::V2018_01_01"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2017-09-preview and ruby

These settings apply only when `--tag=package-2017-09-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2017-09-preview' && $(ruby)
namespace: "Azure::EventGrid::Mgmt::V2017_09_15_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```

### Tag: package-2017-06-preview and ruby

These settings apply only when `--tag=package-2017-06-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

``` yaml $(tag) == 'package-2017-06-preview' && $(ruby)
namespace: "Azure::EventGrid::Mgmt::V2017_06_15_preview"
output-folder: $(ruby-sdks-folder)/management/azure_mgmt_event_grid/lib
```
