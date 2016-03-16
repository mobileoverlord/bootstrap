# Bootstrap

Test with

```
mix deps.get
mix compile
```

You will notice that it will compile exrm app but not any of its deps.

```
Compile from config
==> exrm
Compiled lib/exrm/config.ex
Compiled lib/exrm/utils/logger.ex
Compiled lib/exrm/plugin.ex
Compiled lib/exrm/plugins/appups.ex
Compiled lib/exrm/deps.ex
Compiled lib/exrm/utils/utils.ex
Compiled lib/exrm/plugins/consolidation.ex
Compiled lib/mix/tasks/release.plugins.ex
Compiled lib/exrm/appups.ex
Compiled lib/mix/tasks/release.clean.ex
Compiled lib/mix/tasks/release.ex
Generated exrm app
Success
==> cf (compile)
Compiled src/cf.erl
Compiled src/cf_term.erl
==> erlware_commons (compile)
Compiled src/ec_vsn.erl
...
```
