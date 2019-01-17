# Go rules

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    url = "https://github.com/bazelbuild/rules_go/releases/download/0.16.5/rules_go-0.16.5.tar.gz",
    sha256 = "7be7dc01f1e0afdba6c8eb2b43d2fa01c743be1b9273ab1eaf6c233df078d705",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

# Go Gazelle rules

http_archive(
    name = "bazel_gazelle",
    urls = ["https://github.com/bazelbuild/bazel-gazelle/releases/download/0.16.0/bazel-gazelle-0.16.0.tar.gz"],
    sha256 = "7949fc6cc17b5b191103e97481cf8889217263acf52e00b560683413af204fcb",
)

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()

go_repository(
    name = "co_honnef_go_tools",
    commit = "ae8f1f9103cc",
    importpath = "honnef.co/go/tools",
)

go_repository(
    name = "com_github_alcortesm_tgz",
    commit = "9c5fe88206d7",
    importpath = "github.com/alcortesm/tgz",
)

go_repository(
    name = "com_github_alecthomas_kingpin",
    importpath = "github.com/alecthomas/kingpin",
    tag = "v2.2.6",
)

go_repository(
    name = "com_github_alecthomas_template",
    commit = "a0175ee3bccc",
    importpath = "github.com/alecthomas/template",
)

go_repository(
    name = "com_github_alecthomas_units",
    commit = "2efee857e7cf",
    importpath = "github.com/alecthomas/units",
)

go_repository(
    name = "com_github_andreyvit_diff",
    commit = "c7f18ee00883",
    importpath = "github.com/andreyvit/diff",
)

go_repository(
    name = "com_github_anmitsu_go_shlex",
    commit = "648efa622239",
    importpath = "github.com/anmitsu/go-shlex",
)

go_repository(
    name = "com_github_aokoli_goutils",
    importpath = "github.com/aokoli/goutils",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_apache_arrow_go_arrow",
    commit = "e9ed591db9cb",
    importpath = "github.com/apache/arrow/go/arrow",
)

go_repository(
    name = "com_github_apex_log",
    importpath = "github.com/apex/log",
    tag = "v1.1.0",
)

go_repository(
    name = "com_github_armon_consul_api",
    commit = "eb2c6b5be1b6",
    importpath = "github.com/armon/consul-api",
)

go_repository(
    name = "com_github_armon_go_metrics",
    commit = "f0300d1749da",
    importpath = "github.com/armon/go-metrics",
)

go_repository(
    name = "com_github_armon_go_radix",
    importpath = "github.com/armon/go-radix",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_asaskevich_govalidator",
    commit = "f9ffefc3facf",
    importpath = "github.com/asaskevich/govalidator",
)

go_repository(
    name = "com_github_aws_aws_sdk_go",
    importpath = "github.com/aws/aws-sdk-go",
    tag = "v1.15.64",
)

go_repository(
    name = "com_github_azure_go_ansiterm",
    commit = "d6e3b3328b78",
    importpath = "github.com/Azure/go-ansiterm",
)

go_repository(
    name = "com_github_azure_go_autorest",
    importpath = "github.com/Azure/go-autorest",
    tag = "v10.6.2",
)

go_repository(
    name = "com_github_benbjohnson_tmpl",
    importpath = "github.com/benbjohnson/tmpl",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_beorn7_perks",
    commit = "3a771d992973",
    importpath = "github.com/beorn7/perks",
)

go_repository(
    name = "com_github_bitly_go_hostpool",
    commit = "a3a6125de932",
    importpath = "github.com/bitly/go-hostpool",
)

go_repository(
    name = "com_github_blakesmith_ar",
    commit = "8bd4349a67f2",
    importpath = "github.com/blakesmith/ar",
)

go_repository(
    name = "com_github_bmizerany_assert",
    commit = "b7ed37b82869",
    importpath = "github.com/bmizerany/assert",
)

go_repository(
    name = "com_github_boltdb_bolt",
    importpath = "github.com/boltdb/bolt",
    tag = "v1.3.1",
)

go_repository(
    name = "com_github_bouk_httprouter",
    commit = "ee8b3818a7f5",
    importpath = "github.com/bouk/httprouter",
)

go_repository(
    name = "com_github_burntsushi_toml",
    importpath = "github.com/BurntSushi/toml",
    tag = "v0.3.1",
)

go_repository(
    name = "com_github_c_bata_go_prompt",
    importpath = "github.com/c-bata/go-prompt",
    tag = "v0.2.2",
)

go_repository(
    name = "com_github_caarlos0_ctrlc",
    importpath = "github.com/caarlos0/ctrlc",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_campoy_unique",
    commit = "88950e537e7e",
    importpath = "github.com/campoy/unique",
)

go_repository(
    name = "com_github_cenkalti_backoff",
    importpath = "github.com/cenkalti/backoff",
    tag = "v2.0.0",
)

go_repository(
    name = "com_github_cespare_xxhash",
    importpath = "github.com/cespare/xxhash",
    tag = "v1.1.0",
)

go_repository(
    name = "com_github_circonus_labs_circonus_gometrics",
    importpath = "github.com/circonus-labs/circonus-gometrics",
    tag = "v2.2.5",
)

go_repository(
    name = "com_github_circonus_labs_circonusllhist",
    importpath = "github.com/circonus-labs/circonusllhist",
    tag = "v0.1.3",
)

go_repository(
    name = "com_github_client9_misspell",
    importpath = "github.com/client9/misspell",
    tag = "v0.3.4",
)

go_repository(
    name = "com_github_containerd_continuity",
    commit = "bea7585dbfac",
    importpath = "github.com/containerd/continuity",
)

go_repository(
    name = "com_github_coreos_bbolt",
    importpath = "github.com/coreos/bbolt",
    tag = "v1.3.1-coreos.6",
)

go_repository(
    name = "com_github_coreos_etcd",
    importpath = "github.com/coreos/etcd",
    tag = "v3.3.10",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "com_github_coreos_go_etcd",
    importpath = "github.com/coreos/go-etcd",
    tag = "v2.0.0",
)

go_repository(
    name = "com_github_coreos_go_semver",
    importpath = "github.com/coreos/go-semver",
    tag = "v0.2.0",
)

go_repository(
    name = "com_github_datadog_datadog_go",
    commit = "281ae9f2d895",
    importpath = "github.com/DataDog/datadog-go",
)

go_repository(
    name = "com_github_davecgh_go_spew",
    importpath = "github.com/davecgh/go-spew",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_denisenkom_go_mssqldb",
    commit = "4e0d7dc8888f",
    importpath = "github.com/denisenkom/go-mssqldb",
)

go_repository(
    name = "com_github_dgrijalva_jwt_go",
    importpath = "github.com/dgrijalva/jwt-go",
    tag = "v3.2.0",
)

go_repository(
    name = "com_github_dgryski_go_bitstream",
    commit = "3522498ce2c8",
    importpath = "github.com/dgryski/go-bitstream",
)

go_repository(
    name = "com_github_docker_distribution",
    importpath = "github.com/docker/distribution",
    tag = "v2.6.2",
)

go_repository(
    name = "com_github_docker_docker",
    commit = "57142e89befe",
    importpath = "github.com/docker/docker",
)

go_repository(
    name = "com_github_docker_go_connections",
    importpath = "github.com/docker/go-connections",
    tag = "v0.4.0",
)

go_repository(
    name = "com_github_docker_go_units",
    importpath = "github.com/docker/go-units",
    tag = "v0.3.3",
)

go_repository(
    name = "com_github_docopt_docopt_go",
    commit = "ee0de3bc6815",
    importpath = "github.com/docopt/docopt-go",
)

go_repository(
    name = "com_github_duosecurity_duo_api_golang",
    commit = "92fea9203dbc",
    importpath = "github.com/duosecurity/duo_api_golang",
)

go_repository(
    name = "com_github_dustin_go_humanize",
    importpath = "github.com/dustin/go-humanize",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_eapache_channels",
    importpath = "github.com/eapache/channels",
    tag = "v1.1.0",
)

go_repository(
    name = "com_github_eapache_queue",
    commit = "093482f3f8ce",
    importpath = "github.com/eapache/queue",
)

go_repository(
    name = "com_github_elazarl_go_bindata_assetfs",
    importpath = "github.com/elazarl/go-bindata-assetfs",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_emirpasic_gods",
    importpath = "github.com/emirpasic/gods",
    tag = "v1.9.0",
)

go_repository(
    name = "com_github_fatih_color",
    importpath = "github.com/fatih/color",
    tag = "v1.7.0",
)

go_repository(
    name = "com_github_fatih_structs",
    importpath = "github.com/fatih/structs",
    tag = "v1.1.0",
)

go_repository(
    name = "com_github_flynn_go_shlex",
    commit = "3f9db97f8568",
    importpath = "github.com/flynn/go-shlex",
)

go_repository(
    name = "com_github_fsnotify_fsnotify",
    importpath = "github.com/fsnotify/fsnotify",
    tag = "v1.4.7",
)

go_repository(
    name = "com_github_getkin_kin_openapi",
    importpath = "github.com/getkin/kin-openapi",
    tag = "v0.1.0",
)

go_repository(
    name = "com_github_ghodss_yaml",
    importpath = "github.com/ghodss/yaml",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_gliderlabs_ssh",
    importpath = "github.com/gliderlabs/ssh",
    tag = "v0.1.1",
)

go_repository(
    name = "com_github_glycerine_go_unsnap_stream",
    commit = "9f0cb55181dd",
    importpath = "github.com/glycerine/go-unsnap-stream",
)

go_repository(
    name = "com_github_glycerine_goconvey",
    commit = "46e3a41ad493",
    importpath = "github.com/glycerine/goconvey",
)

go_repository(
    name = "com_github_go_ldap_ldap",
    importpath = "github.com/go-ldap/ldap",
    tag = "v2.5.1",
)

go_repository(
    name = "com_github_go_ole_go_ole",
    importpath = "github.com/go-ole/go-ole",
    tag = "v1.2.2",
)

go_repository(
    name = "com_github_go_sql_driver_mysql",
    importpath = "github.com/go-sql-driver/mysql",
    tag = "v1.4.0",
)

go_repository(
    name = "com_github_go_test_deep",
    importpath = "github.com/go-test/deep",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_gocql_gocql",
    commit = "33c0e89ca93a",
    importpath = "github.com/gocql/gocql",
)

go_repository(
    name = "com_github_gogo_protobuf",
    importpath = "github.com/gogo/protobuf",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_golang_gddo",
    commit = "9bd4a3295021",
    importpath = "github.com/golang/gddo",
)

go_repository(
    name = "com_github_golang_glog",
    commit = "23def4e6c14b",
    importpath = "github.com/golang/glog",
)

go_repository(
    name = "com_github_golang_lint",
    commit = "06c8688daad7",
    importpath = "github.com/golang/lint",
)

go_repository(
    name = "com_github_golang_mock",
    importpath = "github.com/golang/mock",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_golang_protobuf",
    importpath = "github.com/golang/protobuf",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_golang_snappy",
    commit = "2e65f85255db",
    importpath = "github.com/golang/snappy",
)

go_repository(
    name = "com_github_google_btree",
    commit = "4030bb1f1f0c",
    importpath = "github.com/google/btree",
)

go_repository(
    name = "com_github_google_go_cmp",
    importpath = "github.com/google/go-cmp",
    tag = "v0.2.0",
)

go_repository(
    name = "com_github_google_go_github",
    importpath = "github.com/google/go-github",
    tag = "v17.0.0",
)

go_repository(
    name = "com_github_google_go_querystring",
    importpath = "github.com/google/go-querystring",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_google_gofuzz",
    commit = "44d81051d367",
    importpath = "github.com/google/gofuzz",
)

go_repository(
    name = "com_github_google_uuid",
    importpath = "github.com/google/uuid",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_googleapis_gnostic",
    commit = "0c5108395e2d",
    importpath = "github.com/googleapis/gnostic",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "com_github_gophercloud_gophercloud",
    commit = "781450b3c4fc",
    importpath = "github.com/gophercloud/gophercloud",
)

go_repository(
    name = "com_github_gopherjs_gopherjs",
    commit = "0766667cb4d1",
    importpath = "github.com/gopherjs/gopherjs",
)

go_repository(
    name = "com_github_goreleaser_goreleaser",
    importpath = "github.com/goreleaser/goreleaser",
    tag = "v0.94.0",
)

go_repository(
    name = "com_github_goreleaser_nfpm",
    importpath = "github.com/goreleaser/nfpm",
    tag = "v0.9.7",
)

go_repository(
    name = "com_github_gotestyourself_gotestyourself",
    importpath = "github.com/gotestyourself/gotestyourself",
    tag = "v2.2.0",
)

go_repository(
    name = "com_github_gregjones_httpcache",
    commit = "787624de3eb7",
    importpath = "github.com/gregjones/httpcache",
)

go_repository(
    name = "com_github_hailocab_go_hostpool",
    commit = "e80d13ce29ed",
    importpath = "github.com/hailocab/go-hostpool",
)

go_repository(
    name = "com_github_hashicorp_consul",
    importpath = "github.com/hashicorp/consul",
    tag = "v1.4.0",
)

go_repository(
    name = "com_github_hashicorp_errwrap",
    importpath = "github.com/hashicorp/errwrap",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_go_cleanhttp",
    importpath = "github.com/hashicorp/go-cleanhttp",
    tag = "v0.5.0",
)

go_repository(
    name = "com_github_hashicorp_go_hclog",
    commit = "61d530d6c27f",
    importpath = "github.com/hashicorp/go-hclog",
)

go_repository(
    name = "com_github_hashicorp_go_immutable_radix",
    importpath = "github.com/hashicorp/go-immutable-radix",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_go_memdb",
    commit = "032f93b25bec",
    importpath = "github.com/hashicorp/go-memdb",
)

go_repository(
    name = "com_github_hashicorp_go_msgpack",
    commit = "fa3f63826f7c",
    importpath = "github.com/hashicorp/go-msgpack",
)

go_repository(
    name = "com_github_hashicorp_go_multierror",
    importpath = "github.com/hashicorp/go-multierror",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_go_plugin",
    commit = "54b6ff97d818",
    importpath = "github.com/hashicorp/go-plugin",
)

go_repository(
    name = "com_github_hashicorp_go_retryablehttp",
    importpath = "github.com/hashicorp/go-retryablehttp",
    tag = "v0.5.0",
)

go_repository(
    name = "com_github_hashicorp_go_rootcerts",
    commit = "6bb64b370b90",
    importpath = "github.com/hashicorp/go-rootcerts",
)

go_repository(
    name = "com_github_hashicorp_go_sockaddr",
    commit = "6d291a969b86",
    importpath = "github.com/hashicorp/go-sockaddr",
)

go_repository(
    name = "com_github_hashicorp_go_uuid",
    importpath = "github.com/hashicorp/go-uuid",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_go_version",
    importpath = "github.com/hashicorp/go-version",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_golang_lru",
    importpath = "github.com/hashicorp/golang-lru",
    tag = "v0.5.0",
)

go_repository(
    name = "com_github_hashicorp_hcl",
    importpath = "github.com/hashicorp/hcl",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_memberlist",
    importpath = "github.com/hashicorp/memberlist",
    tag = "v0.1.0",
)

go_repository(
    name = "com_github_hashicorp_raft",
    importpath = "github.com/hashicorp/raft",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_hashicorp_serf",
    importpath = "github.com/hashicorp/serf",
    tag = "v0.8.1",
)

go_repository(
    name = "com_github_hashicorp_vault",
    importpath = "github.com/hashicorp/vault",
    tag = "v0.11.5",
)

go_repository(
    name = "com_github_hashicorp_vault_plugin_secrets_kv",
    commit = "2236f141171e",
    importpath = "github.com/hashicorp/vault-plugin-secrets-kv",
)

go_repository(
    name = "com_github_hashicorp_yamux",
    commit = "2f1d1f20f75d",
    importpath = "github.com/hashicorp/yamux",
)

go_repository(
    name = "com_github_hpcloud_tail",
    importpath = "github.com/hpcloud/tail",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_huandu_xstrings",
    importpath = "github.com/huandu/xstrings",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_imdario_mergo",
    importpath = "github.com/imdario/mergo",
    tag = "v0.3.6",
)

go_repository(
    name = "com_github_inconshreveable_mousetrap",
    importpath = "github.com/inconshreveable/mousetrap",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_influxdata_flux",
    importpath = "github.com/influxdata/flux",
    tag = "v0.12.0",
)

go_repository(
    name = "com_github_influxdata_influxdb",
    commit = "dd481f35df2c",
    importpath = "github.com/influxdata/influxdb",
)

go_repository(
    name = "com_github_influxdata_influxql",
    commit = "1cbfca8e56b6",
    importpath = "github.com/influxdata/influxql",
)

go_repository(
    name = "com_github_influxdata_line_protocol",
    commit = "32c6aa80de5e",
    importpath = "github.com/influxdata/line-protocol",
)

go_repository(
    name = "com_github_influxdata_platform",
    commit = "4ca3b83813d1",
    importpath = "github.com/influxdata/platform",
)

go_repository(
    name = "com_github_influxdata_tdigest",
    commit = "bf2b5ad3c0a9",
    importpath = "github.com/influxdata/tdigest",
)

go_repository(
    name = "com_github_influxdata_usage_client",
    commit = "6d3895376368",
    importpath = "github.com/influxdata/usage-client",
)

go_repository(
    name = "com_github_jbenet_go_context",
    commit = "d14ea06fba99",
    importpath = "github.com/jbenet/go-context",
)

go_repository(
    name = "com_github_jeffail_gabs",
    importpath = "github.com/Jeffail/gabs",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_jefferai_jsonx",
    commit = "9cc31c3135ee",
    importpath = "github.com/jefferai/jsonx",
)

go_repository(
    name = "com_github_jessevdk_go_flags",
    importpath = "github.com/jessevdk/go-flags",
    tag = "v1.4.0",
)

go_repository(
    name = "com_github_jmespath_go_jmespath",
    commit = "c2b33e8439af",
    importpath = "github.com/jmespath/go-jmespath",
)

go_repository(
    name = "com_github_json_iterator_go",
    commit = "f2b4162afba3",
    importpath = "github.com/json-iterator/go",
)

go_repository(
    name = "com_github_jsternberg_zap_logfmt",
    importpath = "github.com/jsternberg/zap-logfmt",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_jtolds_gls",
    importpath = "github.com/jtolds/gls",
    tag = "v4.2.1",
)

go_repository(
    name = "com_github_julienschmidt_httprouter",
    importpath = "github.com/julienschmidt/httprouter",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_jwilder_encoding",
    commit = "b4e1701a28ef",
    importpath = "github.com/jwilder/encoding",
)

go_repository(
    name = "com_github_k0kubun_colorstring",
    commit = "9440f1994b88",
    importpath = "github.com/k0kubun/colorstring",
)

go_repository(
    name = "com_github_kelseyhightower_envconfig",
    commit = "dd1402a4d99d",
    importpath = "github.com/kelseyhightower/envconfig",
)

go_repository(
    name = "com_github_kevinburke_go_bindata",
    importpath = "github.com/kevinburke/go-bindata",
    tag = "v3.11.0",
)

go_repository(
    name = "com_github_kevinburke_ssh_config",
    commit = "81db2a75821e",
    importpath = "github.com/kevinburke/ssh_config",
)

go_repository(
    name = "com_github_keybase_go_crypto",
    commit = "f919bfda4fc1",
    importpath = "github.com/keybase/go-crypto",
)

go_repository(
    name = "com_github_kisielk_gotool",
    importpath = "github.com/kisielk/gotool",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_konsorten_go_windows_terminal_sequences",
    importpath = "github.com/konsorten/go-windows-terminal-sequences",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_kr_pretty",
    importpath = "github.com/kr/pretty",
    tag = "v0.1.0",
)

go_repository(
    name = "com_github_kr_pty",
    importpath = "github.com/kr/pty",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_kr_text",
    importpath = "github.com/kr/text",
    tag = "v0.1.0",
)

go_repository(
    name = "com_github_lib_pq",
    importpath = "github.com/lib/pq",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_magiconair_properties",
    importpath = "github.com/magiconair/properties",
    tag = "v1.8.0",
)

go_repository(
    name = "com_github_masterminds_semver",
    importpath = "github.com/Masterminds/semver",
    tag = "v1.4.2",
)

go_repository(
    name = "com_github_masterminds_sprig",
    importpath = "github.com/Masterminds/sprig",
    tag = "v2.16.0",
)

go_repository(
    name = "com_github_mattn_go_colorable",
    importpath = "github.com/mattn/go-colorable",
    tag = "v0.0.9",
)

go_repository(
    name = "com_github_mattn_go_isatty",
    importpath = "github.com/mattn/go-isatty",
    tag = "v0.0.4",
)

go_repository(
    name = "com_github_mattn_go_runewidth",
    importpath = "github.com/mattn/go-runewidth",
    tag = "v0.0.3",
)

go_repository(
    name = "com_github_mattn_go_tty",
    commit = "13ff1204f104",
    importpath = "github.com/mattn/go-tty",
)

go_repository(
    name = "com_github_mattn_go_zglob",
    commit = "2ea3427bfa53",
    importpath = "github.com/mattn/go-zglob",
)

go_repository(
    name = "com_github_matttproud_golang_protobuf_extensions",
    importpath = "github.com/matttproud/golang_protobuf_extensions",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_mcuadros_go_version",
    commit = "6d5863ca60fa",
    importpath = "github.com/mcuadros/go-version",
)

go_repository(
    name = "com_github_microsoft_go_winio",
    importpath = "github.com/Microsoft/go-winio",
    tag = "v0.4.11",
)

go_repository(
    name = "com_github_miekg_dns",
    importpath = "github.com/miekg/dns",
    tag = "v1.1.1",
)

go_repository(
    name = "com_github_mitchellh_copystructure",
    importpath = "github.com/mitchellh/copystructure",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_mitchellh_go_homedir",
    importpath = "github.com/mitchellh/go-homedir",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_mitchellh_go_testing_interface",
    importpath = "github.com/mitchellh/go-testing-interface",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_mitchellh_mapstructure",
    importpath = "github.com/mitchellh/mapstructure",
    tag = "v1.1.2",
)

go_repository(
    name = "com_github_mitchellh_reflectwalk",
    importpath = "github.com/mitchellh/reflectwalk",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_mna_pigeon",
    importpath = "github.com/mna/pigeon",
    tag = "v1.0.1-0.20180808201053-bb0192cfc2ae",
)

go_repository(
    name = "com_github_modern_go_concurrent",
    commit = "bacd9c7ef1dd",
    importpath = "github.com/modern-go/concurrent",
)

go_repository(
    name = "com_github_modern_go_reflect2",
    commit = "05fbef0ca5da",
    importpath = "github.com/modern-go/reflect2",
)

go_repository(
    name = "com_github_mschoch_smat",
    commit = "90eadee771ae",
    importpath = "github.com/mschoch/smat",
)

go_repository(
    name = "com_github_nats_io_gnatsd",
    importpath = "github.com/nats-io/gnatsd",
    tag = "v1.3.0",
)

go_repository(
    name = "com_github_nats_io_go_nats",
    importpath = "github.com/nats-io/go-nats",
    tag = "v1.6.0",
)

go_repository(
    name = "com_github_nats_io_go_nats_streaming",
    importpath = "github.com/nats-io/go-nats-streaming",
    tag = "v0.4.0",
)

go_repository(
    name = "com_github_nats_io_nats_streaming_server",
    importpath = "github.com/nats-io/nats-streaming-server",
    tag = "v0.11.2",
)

go_repository(
    name = "com_github_nats_io_nuid",
    importpath = "github.com/nats-io/nuid",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_nvveen_gotty",
    commit = "cd527374f1e5",
    importpath = "github.com/Nvveen/Gotty",
)

go_repository(
    name = "com_github_nytimes_gziphandler",
    importpath = "github.com/NYTimes/gziphandler",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_oklog_run",
    importpath = "github.com/oklog/run",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_olekukonko_tablewriter",
    importpath = "github.com/olekukonko/tablewriter",
    tag = "v0.0.1",
)

go_repository(
    name = "com_github_oneofone_xxhash",
    importpath = "github.com/OneOfOne/xxhash",
    tag = "v1.2.2",
)

go_repository(
    name = "com_github_onsi_ginkgo",
    importpath = "github.com/onsi/ginkgo",
    tag = "v1.7.0",
)

go_repository(
    name = "com_github_onsi_gomega",
    importpath = "github.com/onsi/gomega",
    tag = "v1.4.3",
)

go_repository(
    name = "com_github_opencontainers_go_digest",
    importpath = "github.com/opencontainers/go-digest",
    tag = "v1.0.0-rc1",
)

go_repository(
    name = "com_github_opencontainers_image_spec",
    importpath = "github.com/opencontainers/image-spec",
    tag = "v1.0.1",
)

go_repository(
    name = "com_github_opencontainers_runc",
    importpath = "github.com/opencontainers/runc",
    tag = "v0.1.1",
)

go_repository(
    name = "com_github_opentracing_opentracing_go",
    importpath = "github.com/opentracing/opentracing-go",
    tag = "v1.0.2",
)

go_repository(
    name = "com_github_ory_dockertest",
    importpath = "github.com/ory/dockertest",
    tag = "v3.3.2",
)

go_repository(
    name = "com_github_osrg_gobgp",
    commit = "bbd1d99396fe",
    importpath = "github.com/osrg/gobgp",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "com_github_pascaldekloe_goe",
    commit = "57f6aae5913c",
    importpath = "github.com/pascaldekloe/goe",
)

go_repository(
    name = "com_github_patrickmn_go_cache",
    importpath = "github.com/patrickmn/go-cache",
    tag = "v2.1.0",
)

go_repository(
    name = "com_github_pborman_uuid",
    commit = "ca53cad383ca",
    importpath = "github.com/pborman/uuid",
)

go_repository(
    name = "com_github_pelletier_go_buffruneio",
    importpath = "github.com/pelletier/go-buffruneio",
    tag = "v0.2.0",
)

go_repository(
    name = "com_github_pelletier_go_toml",
    importpath = "github.com/pelletier/go-toml",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_peterbourgon_diskv",
    importpath = "github.com/peterbourgon/diskv",
    tag = "v2.0.1",
)

go_repository(
    name = "com_github_philhofer_fwd",
    importpath = "github.com/philhofer/fwd",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_pierrec_lz4",
    importpath = "github.com/pierrec/lz4",
    tag = "v2.0.5",
)

go_repository(
    name = "com_github_pkg_errors",
    importpath = "github.com/pkg/errors",
    tag = "v0.8.0",
)

go_repository(
    name = "com_github_pkg_term",
    commit = "bffc007b7fd5",
    importpath = "github.com/pkg/term",
)

go_repository(
    name = "com_github_pmezard_go_difflib",
    importpath = "github.com/pmezard/go-difflib",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_projectcalico_go_json",
    commit = "6219dc7339ba",
    importpath = "github.com/projectcalico/go-json",
)

go_repository(
    name = "com_github_projectcalico_go_yaml",
    commit = "955bc3e451ef",
    importpath = "github.com/projectcalico/go-yaml",
)

go_repository(
    name = "com_github_projectcalico_go_yaml_wrapper",
    commit = "598e54215bee",
    importpath = "github.com/projectcalico/go-yaml-wrapper",
)

go_repository(
    name = "com_github_projectcalico_libcalico_go",
    commit = "3930d9445d83",
    importpath = "github.com/projectcalico/libcalico-go",
)

go_repository(
    name = "com_github_prometheus_client_golang",
    importpath = "github.com/prometheus/client_golang",
    tag = "v0.9.0",
)

go_repository(
    name = "com_github_prometheus_client_model",
    commit = "5c3871d89910",
    importpath = "github.com/prometheus/client_model",
)

go_repository(
    name = "com_github_prometheus_common",
    commit = "7e9e6cabbd39",
    importpath = "github.com/prometheus/common",
)

go_repository(
    name = "com_github_prometheus_procfs",
    commit = "185b4288413d",
    importpath = "github.com/prometheus/procfs",
)

go_repository(
    name = "com_github_roaringbitmap_roaring",
    importpath = "github.com/RoaringBitmap/roaring",
    tag = "v0.4.16",
)

go_repository(
    name = "com_github_ryanuber_go_glob",
    commit = "256dc444b735",
    importpath = "github.com/ryanuber/go-glob",
)

go_repository(
    name = "com_github_sap_go_hdb",
    importpath = "github.com/SAP/go-hdb",
    tag = "v0.13.1",
)

go_repository(
    name = "com_github_satori_go_uuid",
    importpath = "github.com/satori/go.uuid",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_sean__seed",
    commit = "e2103e2c3529",
    importpath = "github.com/sean-/seed",
)

go_repository(
    name = "com_github_segmentio_kafka_go",
    importpath = "github.com/segmentio/kafka-go",
    tag = "v0.1.0",
)

go_repository(
    name = "com_github_sergi_go_diff",
    importpath = "github.com/sergi/go-diff",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_sermodigital_jose",
    importpath = "github.com/SermoDigital/jose",
    tag = "v0.9.1",
)

go_repository(
    name = "com_github_shirou_gopsutil",
    commit = "db425313bfa8",
    importpath = "github.com/shirou/gopsutil",
)

go_repository(
    name = "com_github_shirou_w32",
    commit = "bb4de0191aa4",
    importpath = "github.com/shirou/w32",
)

go_repository(
    name = "com_github_sirupsen_logrus",
    importpath = "github.com/sirupsen/logrus",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_smartystreets_assertions",
    commit = "b2de0cb4f26d",
    importpath = "github.com/smartystreets/assertions",
)

go_repository(
    name = "com_github_smartystreets_goconvey",
    commit = "ef6db91d284a",
    importpath = "github.com/smartystreets/goconvey",
)

go_repository(
    name = "com_github_spaolacci_murmur3",
    commit = "f09979ecbc72",
    importpath = "github.com/spaolacci/murmur3",
)

go_repository(
    name = "com_github_spf13_afero",
    importpath = "github.com/spf13/afero",
    tag = "v1.2.0",
)

go_repository(
    name = "com_github_spf13_cast",
    importpath = "github.com/spf13/cast",
    tag = "v1.3.0",
)

go_repository(
    name = "com_github_spf13_cobra",
    importpath = "github.com/spf13/cobra",
    tag = "v0.0.3",
)

go_repository(
    name = "com_github_spf13_jwalterweatherman",
    importpath = "github.com/spf13/jwalterweatherman",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_spf13_pflag",
    importpath = "github.com/spf13/pflag",
    tag = "v1.0.3",
)

go_repository(
    name = "com_github_spf13_viper",
    importpath = "github.com/spf13/viper",
    tag = "v1.3.1",
)

go_repository(
    name = "com_github_src_d_gcfg",
    importpath = "github.com/src-d/gcfg",
    tag = "v1.4.0",
)

go_repository(
    name = "com_github_stackexchange_wmi",
    commit = "e0a55b97c705",
    importpath = "github.com/StackExchange/wmi",
)

go_repository(
    name = "com_github_stevvooe_resumable",
    commit = "22b14a53ba50",
    importpath = "github.com/stevvooe/resumable",
)

go_repository(
    name = "com_github_stretchr_objx",
    importpath = "github.com/stretchr/objx",
    tag = "v0.1.1",
)

go_repository(
    name = "com_github_stretchr_testify",
    importpath = "github.com/stretchr/testify",
    tag = "v1.2.2",
)

go_repository(
    name = "com_github_tcnksm_go_input",
    commit = "548a7d7a8ee8",
    importpath = "github.com/tcnksm/go-input",
)

go_repository(
    name = "com_github_termie_go_shutil",
    commit = "bcacb06fecae",
    importpath = "github.com/termie/go-shutil",
)

go_repository(
    name = "com_github_testcontainers_testcontainer_go",
    commit = "8e868ca12c0f",
    importpath = "github.com/testcontainers/testcontainer-go",
)

go_repository(
    name = "com_github_tinylib_msgp",
    importpath = "github.com/tinylib/msgp",
    tag = "v1.0.2",
)

go_repository(
    name = "com_github_tv42_httpunix",
    commit = "b75d8614f926",
    importpath = "github.com/tv42/httpunix",
)

go_repository(
    name = "com_github_tylerb_graceful",
    importpath = "github.com/tylerb/graceful",
    tag = "v1.2.15",
)

go_repository(
    name = "com_github_ugorji_go_codec",
    commit = "d75b2dcb6bc8",
    importpath = "github.com/ugorji/go/codec",
)

go_repository(
    name = "com_github_vishvananda_netlink",
    commit = "f07d9d5231b9",
    importpath = "github.com/vishvananda/netlink",
)

go_repository(
    name = "com_github_vishvananda_netns",
    commit = "54f0e4339ce7",
    importpath = "github.com/vishvananda/netns",
)

go_repository(
    name = "com_github_willf_bitset",
    importpath = "github.com/willf/bitset",
    tag = "v1.1.9",
)

go_repository(
    name = "com_github_xanzy_ssh_agent",
    importpath = "github.com/xanzy/ssh-agent",
    tag = "v0.2.0",
)

go_repository(
    name = "com_github_xordataexchange_crypt",
    importpath = "github.com/xordataexchange/crypt",
    tag = "v0.0.3-0.20170626215501-b2862e3d0a77",
)

go_repository(
    name = "com_github_yudai_gojsondiff",
    importpath = "github.com/yudai/gojsondiff",
    tag = "v1.0.0",
)

go_repository(
    name = "com_github_yudai_golcs",
    commit = "ecda9a501e82",
    importpath = "github.com/yudai/golcs",
)

go_repository(
    name = "com_github_yudai_pp",
    importpath = "github.com/yudai/pp",
    tag = "v2.0.1",
)

go_repository(
    name = "com_google_cloud_go",
    importpath = "cloud.google.com/go",
    tag = "v0.26.0",
)

go_repository(
    name = "in_gopkg_asn1_ber_v1",
    commit = "379148ca0225",
    importpath = "gopkg.in/asn1-ber.v1",
)

go_repository(
    name = "in_gopkg_check_v1",
    commit = "788fd7840127",
    importpath = "gopkg.in/check.v1",
)

go_repository(
    name = "in_gopkg_fsnotify_fsnotify_v1",
    importpath = "gopkg.in/fsnotify/fsnotify.v1",
    tag = "v1.4.7",
)

go_repository(
    name = "in_gopkg_fsnotify_v1",
    importpath = "gopkg.in/fsnotify.v1",
    tag = "v1.4.7",
)

go_repository(
    name = "in_gopkg_go_playground_validator_v8",
    importpath = "gopkg.in/go-playground/validator.v8",
    tag = "v8.18.2",
)

go_repository(
    name = "in_gopkg_inf_v0",
    importpath = "gopkg.in/inf.v0",
    tag = "v0.9.1",
)

go_repository(
    name = "in_gopkg_ldap_v2",
    importpath = "gopkg.in/ldap.v2",
    tag = "v2.5.1",
)

go_repository(
    name = "in_gopkg_mgo_v2",
    commit = "9856a29383ce",
    importpath = "gopkg.in/mgo.v2",
)

go_repository(
    name = "in_gopkg_robfig_cron_v2",
    commit = "be2e0b0deed5",
    importpath = "gopkg.in/robfig/cron.v2",
)

go_repository(
    name = "in_gopkg_src_d_go_billy_v4",
    importpath = "gopkg.in/src-d/go-billy.v4",
    tag = "v4.2.1",
)

go_repository(
    name = "in_gopkg_src_d_go_git_fixtures_v3",
    importpath = "gopkg.in/src-d/go-git-fixtures.v3",
    tag = "v3.1.1",
)

go_repository(
    name = "in_gopkg_src_d_go_git_v4",
    importpath = "gopkg.in/src-d/go-git.v4",
    tag = "v4.8.1",
)

go_repository(
    name = "in_gopkg_tomb_v1",
    commit = "dd632973f1e7",
    importpath = "gopkg.in/tomb.v1",
)

go_repository(
    name = "in_gopkg_tomb_v2",
    commit = "d5d1b5820637",
    importpath = "gopkg.in/tomb.v2",
)

go_repository(
    name = "in_gopkg_vmihailenco_msgpack_v2",
    importpath = "gopkg.in/vmihailenco/msgpack.v2",
    tag = "v2.9.1",
)

go_repository(
    name = "in_gopkg_warnings_v0",
    importpath = "gopkg.in/warnings.v0",
    tag = "v0.1.2",
)

go_repository(
    name = "in_gopkg_yaml_v2",
    importpath = "gopkg.in/yaml.v2",
    tag = "v2.2.2",
)

go_repository(
    name = "io_k8s_api",
    commit = "072894a440bd",
    importpath = "k8s.io/api",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "io_k8s_apimachinery",
    commit = "103fd098999d",
    importpath = "k8s.io/apimachinery",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "io_k8s_client_go",
    importpath = "k8s.io/client-go",
    tag = "v8.0.0",
    build_file_proto_mode = "disable_global",
)

go_repository(
    name = "net_launchpad_gocheck",
    commit = "000000000087",
    importpath = "launchpad.net/gocheck",
)

go_repository(
    name = "org_golang_google_api",
    commit = "a2651947f503",
    importpath = "google.golang.org/api",
)

go_repository(
    name = "org_golang_google_appengine",
    importpath = "google.golang.org/appengine",
    tag = "v1.3.0",
)

go_repository(
    name = "org_golang_google_genproto",
    commit = "94acd270e44e",
    importpath = "google.golang.org/genproto",
)

go_repository(
    name = "org_golang_google_grpc",
    importpath = "google.golang.org/grpc",
    tag = "v1.15.0",
)

go_repository(
    name = "org_golang_x_crypto",
    commit = "505ab145d0a9",
    importpath = "golang.org/x/crypto",
)

go_repository(
    name = "org_golang_x_exp",
    commit = "a3060d491354",
    importpath = "golang.org/x/exp",
)

go_repository(
    name = "org_golang_x_lint",
    commit = "06c8688daad7",
    importpath = "golang.org/x/lint",
)

go_repository(
    name = "org_golang_x_net",
    commit = "9b4f9f5ad519",
    importpath = "golang.org/x/net",
)

go_repository(
    name = "org_golang_x_oauth2",
    commit = "9dcd33a902f4",
    importpath = "golang.org/x/oauth2",
)

go_repository(
    name = "org_golang_x_sync",
    commit = "1d60e4601c6f",
    importpath = "golang.org/x/sync",
)

go_repository(
    name = "org_golang_x_sys",
    commit = "a5c9d58dba9a",
    importpath = "golang.org/x/sys",
)

go_repository(
    name = "org_golang_x_text",
    importpath = "golang.org/x/text",
    tag = "v0.3.0",
)

go_repository(
    name = "org_golang_x_time",
    commit = "fbb02b2291d2",
    importpath = "golang.org/x/time",
)

go_repository(
    name = "org_golang_x_tools",
    commit = "3ad2d988d5e2",
    importpath = "golang.org/x/tools",
)

go_repository(
    name = "org_gonum_v1_gonum",
    commit = "3f7ecaa7e8ca",
    importpath = "gonum.org/v1/gonum",
)

go_repository(
    name = "org_gonum_v1_netlib",
    commit = "ec6d1f5cefe6",
    importpath = "gonum.org/v1/netlib",
)

go_repository(
    name = "org_labix_v2_mgo",
    commit = "000000000287",
    importpath = "labix.org/v2/mgo",
)

go_repository(
    name = "org_uber_go_atomic",
    importpath = "go.uber.org/atomic",
    tag = "v1.3.2",
)

go_repository(
    name = "org_uber_go_multierr",
    importpath = "go.uber.org/multierr",
    tag = "v1.1.0",
)

go_repository(
    name = "org_uber_go_zap",
    importpath = "go.uber.org/zap",
    tag = "v1.9.1",
)

go_repository(
    name = "tools_gotest",
    importpath = "gotest.tools",
    tag = "v2.2.0",
)
