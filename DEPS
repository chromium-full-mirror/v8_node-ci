# Copyright 2019 the V8 project authors. All rights reserved.
# Use of this source code is governed by a BSD-style license that can be
# found in the LICENSE file.

use_relative_paths = True

gclient_gn_args_file = 'build/config/gclient_args.gni'
gclient_gn_args = [
  'build_upstream_node',
]

vars = {
  # Set to true to use deps bundled in node.
  'build_upstream_node': False,

  'abseil_revision': '1e18dc54a045a632de52d420e9636072662841b4',
  'abseil_url': 'https://chromium.googlesource.com/chromium/src/third_party/abseil-cpp.git',

  'build_revision': '1e0c06afa5ad768c5a98f299dab8f4831f8c5acb',
  'build_url': 'https://chromium.googlesource.com/chromium/src/build.git',

  'buildtools_revision': '6155afa651b6544404544302dce843c1c7dda72c',
  'buildtools_url': 'https://chromium.googlesource.com/chromium/src/buildtools.git',

  'buildtools_clang_format_revision': '1549a8dba21b6c022c6f5ccee4edf18e5ceb2109',
  'buildtools_clang_format_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/clang/tools/clang-format.git',

  'buildtools_libcxx_revision': '9c12a0833f9b62a1aafeb612479653c498845a92',
  'buildtools_libcxx_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/libcxx.git',

  'buildtools_libcxxabi_revision': '6c4fa00e4becc30085cbc8b44c2764ef307daae2',
  'buildtools_libcxxabi_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/libcxxabi.git',

  'buildtools_llvm_libc_revision': 'd8809b0a2e6edd91a9467892ec29315616784973',
  'buildtools_llvm_libc_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/libc.git',

  'buildtools_libunwind_revision': '6066b149576465160ac0d935aa644ec6d3bfb2bf',
  'buildtools_libunwind_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/libunwind.git',

  'compiler_rt_revision': 'd1f4ff49d7d71c2501d32848c9eeb707f857bd4a',
  'compiler_rt_url': 'https://chromium.googlesource.com/external/github.com/llvm/llvm-project/compiler-rt.git',

  'clang_revision': '719a5340defded624fbfd83347006ad950ee0b90',
  'clang_url': 'https://chromium.googlesource.com/chromium/src/tools/clang.git',

  'depot_tools_revision': '80d1969422e75e8e9eecafa46074074b289e2568',
  'depot_tools_url': 'https://chromium.googlesource.com/chromium/tools/depot_tools.git',

  # Fetch configuration files required for the 'use_remoteexec' gn arg
  'download_remoteexec_cfg': False,

  # GN CIPD package version.
  'gn_version': 'git_revision:e5c4d1881b85b82789b7013233a944cf1a46370f',

  # ninja CIPD package version.
  # https://chrome-infra-packages.appspot.com/p/infra/3pp/tools/ninja
  'ninja_version': 'version:3@1.12.1.chromium.4',

  # siso CIPD package version
  'siso_version': 'git_revision:963177240b1a36697c9762856f51ad36ab545ceb',

  'dragonbox_revision': '6c7c925b571d54486b9ffae8d9d18a822801cbda',
  'dragonbox_url': 'https://chromium.googlesource.com/external/github.com/jk-jeon/dragonbox.git',

  'fast_float_revision': 'cb1d42aaa1e14b09e1452cfdef373d051b8c02a4',
  'fast_float_url': 'https://chromium.googlesource.com/external/github.com/fastfloat/fast_float.git',

  'fp16_revision': '98b0a46bce017382a6351a19577ec43a715b6835',
  'fp16_url': 'https://chromium.googlesource.com/external/github.com/Maratyszcza/FP16.git',

  'googletest_revision': '373af2e3df71599b87a40ce0e37164523849166b',
  'googletest_url': 'https://chromium.googlesource.com/external/github.com/google/googletest.git',

  'highway_revision': '00fe003dac355b979f36157f9407c7c46448958e',
  'highway_url': 'https://chromium.googlesource.com/external/github.com/google/highway.git',

  'icu_revision': '1b2e3e8a421efae36141a7b932b41e315b089af8',
  'icu_url': 'https://chromium.googlesource.com/chromium/deps/icu.git',

  'jinja2_revision': '5e1ee241ab04b38889f8d517f2da8b3df7cfbd9a',
  'jinja2_url': 'https://chromium.googlesource.com/chromium/src/third_party/jinja2.git',

  'markupsafe_revision': '9f8efc8637f847ab1ba984212598e6fb9cf1b3d4',
  'markupsafe_url': 'https://chromium.googlesource.com/chromium/src/third_party/markupsafe.git',

  'node_revision': '48abd2f7ae2bea9c0136d9d75d140954f7d82c62',
  'node_url': 'https://chromium.googlesource.com/external/github.com/v8/node.git',

  'trace_common_revision' : '148c806f46c0f8d2e5e888a8175b656ad4cfee43',
  'trace_common_url': 'https://chromium.googlesource.com/chromium/src/base/trace_event/common.git',

  'v8_revision': 'cb11b8ad256576f69a6ddc646aceae2f01f5c23c',
  'v8_url': 'https://chromium.googlesource.com/v8/v8.git',

  'zlib_revision': '5634698162b2182c350e4cb360a0f4dd7706afec',
  'zlib_url': 'https://chromium.googlesource.com/chromium/src/third_party/zlib.git',

  'simdutf_revision': '9d3e4d7c1afb30ed528443d73afab23f22443434',
  'simdutf_url': 'https://chromium.googlesource.com/chromium/src/third_party/simdutf.git',

  'perfetto_revision': 'aa4d8267bafad6782a1f2c8d979104f2aaa622a0',
  'perfetto_url': 'https://android.googlesource.com/platform/external/perfetto.git',

  'protobuf_revision': 'cd23b39adb8c3c2c1a320af29387d101ec48cfe4',
  'protobuf_url': 'https://chromium.googlesource.com/chromium/src/third_party/protobuf.git',

  'jsoncpp_revision': '42e892d96e47b1f6e29844cc705e148ec4856448',
  'jsoncpp_url': 'https://chromium.googlesource.com/external/github.com/open-source-parsers/jsoncpp.git',

  'reclient_version': 're_client_version:0.179.0.28341fc7-gomaip',

  # RBE instance to use for running remote builds
  'rbe_instance': Str('projects/rbe-chrome-untrusted/instances/default_instance'),

  # RBE project to download rewrapper config files for. Only needed if
  # different from the project used in 'rbe_instance'
  'rewrapper_cfg_project': Str(''),
}

deps = {
  'base/trace_event/common': {
    'url': Var('trace_common_url') + '@' + Var('trace_common_revision'),
    'condition': 'not build_upstream_node',
  },
  'build': Var('build_url') + '@' + Var('build_revision'),
  'buildtools': Var('buildtools_url') + '@' + Var('buildtools_revision'),
  'third_party/compiler-rt/src': Var('compiler_rt_url') + '@' + Var('compiler_rt_revision'),
  'third_party/clang-format/script': Var('buildtools_clang_format_url') + '@' + Var('buildtools_clang_format_revision'),
  'third_party/libc++/src': Var('buildtools_libcxx_url') + '@' + Var('buildtools_libcxx_revision'),
  'third_party/libc++abi/src': Var('buildtools_libcxxabi_url') + '@' + Var('buildtools_libcxxabi_revision'),
  'third_party/llvm-libc/src': Var('buildtools_llvm_libc_url') + '@' + Var('buildtools_llvm_libc_revision'),
  'third_party/libunwind/src': Var('buildtools_libunwind_url') + '@' + Var('buildtools_libunwind_revision'),
  'node': Var('node_url') + '@' + Var('node_revision'),
  'third_party/abseil-cpp': Var('abseil_url') + '@' + Var('abseil_revision'),
  'third_party/depot_tools': Var('depot_tools_url') + '@' + Var('depot_tools_revision'),
  'third_party/dragonbox/src': Var('dragonbox_url') + '@' + Var('dragonbox_revision'),
  'third_party/fast_float/src': Var('fast_float_url') + '@' + Var('fast_float_revision'),
  'third_party/fp16/src': {
    'url': Var('fp16_url') + '@' + Var('fp16_revision'),
    'condition': 'not build_upstream_node',
  },
  'third_party/googletest/src': {
    'url': Var('googletest_url') + '@' + Var('googletest_revision'),
    'condition': 'not build_upstream_node',
  },
  'third_party/highway/src': Var('highway_url') + '@' + Var('highway_revision'),
  'third_party/icu': Var('icu_url') + '@' + Var('icu_revision'),
  'third_party/jinja2': Var('jinja2_url') + '@' + Var('jinja2_revision'),
  'third_party/markupsafe': Var('markupsafe_url') + '@' + Var('markupsafe_revision'),
  'third_party/zlib': Var('zlib_url') + '@' + Var('zlib_revision'),
  'third_party/simdutf': Var('simdutf_url') + '@' + Var('simdutf_revision'),
  'third_party/perfetto': Var('perfetto_url') + '@' + Var('perfetto_revision'),
  'third_party/protobuf': Var('protobuf_url') + '@' + Var('protobuf_revision'),
  'third_party/jsoncpp/source': Var('jsoncpp_url') + '@' + Var('jsoncpp_revision'),
  'tools/clang': Var('clang_url') + '@' + Var('clang_revision'),
  'v8': {
    'url': Var('v8_url') + '@' +  Var('v8_revision'),
    'condition': 'not build_upstream_node',
  },
  'buildtools/linux64': {
    'packages': [
      {
        'package': 'gn/gn/linux-${{arch}}',
        'version': Var('gn_version'),
      }
    ],
    'dep_type': 'cipd',
    'condition': 'host_os == "linux"',
  },
  'buildtools/mac': {
    'packages': [
      {
        'package': 'gn/gn/mac-${{arch}}',
        'version': Var('gn_version'),
      }
    ],
    'dep_type': 'cipd',
    'condition': 'host_os == "mac"',
  },
  'buildtools/win': {
    'packages': [
      {
        'package': 'gn/gn/windows-amd64',
        'version': Var('gn_version'),
      }
    ],
    'dep_type': 'cipd',
    'condition': 'host_os == "win"',
  },
  'buildtools/reclient': {
    'packages': [
      {
        'package': 'infra/rbe/client/${{platform}}',
        'version': Var('reclient_version'),
      }
    ],
    'dep_type': 'cipd',
    'condition': '(host_os == "linux" or host_os == "mac" or host_os == "win") and (host_cpu != "arm64" or host_os == "mac")',
  },
  'third_party/ninja': {
    'packages': [
      {
        'package': 'infra/3pp/tools/ninja/${{platform}}',
        'version': Var('ninja_version'),
      }
    ],
    'dep_type': 'cipd',
  },
  'third_party/siso': {
    'packages': [
      {
        'package': 'infra/build/siso/${{platform}}',
        'version': Var('siso_version'),
      }
    ],
    'dep_type': 'cipd',
    'condition': 'host_cpu != "s390" and host_os != "zos" and host_cpu != "ppc"',
  },
}

hooks = [
  {
    # This clobbers when necessary (based on get_landmines.py). It must be the
    # first hook so that other things that get/generate into the output
    # directory will not subsequently be clobbered.
    'name': 'landmines',
    'pattern': '.',
    'action': [
        'python3',
        'build/landmines.py',
        '--landmine-scripts',
        'tools/get_landmines.py',
    ],
  },
  {
    # Update the Windows toolchain if necessary.
    'name': 'win_toolchain',
    'pattern': '.',
    'condition': 'checkout_win',
    'action': ['python3', 'build/vs_toolchain.py', 'update'],
  },
  {
    # Update the Mac toolchain if necessary.
    'name': 'mac_toolchain',
    'pattern': '.',
    'condition': 'checkout_mac',
    'action': ['python3', 'build/mac_toolchain.py'],
  },
  {
    'name': 'clang',
    'pattern': '.',
    'action': ['python3', 'tools/clang/scripts/update.py'],
  },
  {
    # Update LASTCHANGE.
    'name': 'lastchange',
    'pattern': '.',
    'action': ['python3', 'build/util/lastchange.py',
               '-o', 'build/util/LASTCHANGE'],
  },
  {
    'name': 'sysroot_arm',
    'pattern': '.',
    'condition': '(checkout_linux and checkout_arm)',
    'action': ['python3',
               'build/linux/sysroot_scripts/install-sysroot.py',
               '--arch=arm'],
  },
  {
    'name': 'sysroot_arm64',
    'pattern': '.',
    'condition': '(checkout_linux and checkout_arm64)',
    'action': ['python3',
               'build/linux/sysroot_scripts/install-sysroot.py',
               '--arch=arm64'],
  },
  {
    'name': 'sysroot_x86',
    'pattern': '.',
    'condition': '(checkout_linux and (checkout_x86 or checkout_x64))',
    'action': ['python3',
               'build/linux/sysroot_scripts/install-sysroot.py',
               '--arch=x86'],
  },
  {
    'name': 'sysroot_x64',
    'pattern': '.',
    'condition': 'checkout_linux and checkout_x64',
    'action': ['python3',
               'build/linux/sysroot_scripts/install-sysroot.py',
               '--arch=x64'],
  },

  # Configure remote exec cfg files
  {
    'name': 'configure_reclient_cfgs',
    'pattern': '.',
    'condition': 'download_remoteexec_cfg',
    'action': ['python3',
               'buildtools/reclient_cfgs/configure_reclient_cfgs.py',
               '--rbe_instance',
               Var('rbe_instance'),
               '--reproxy_cfg_template',
               'reproxy.cfg.template',
               '--rewrapper_cfg_project',
               Var('rewrapper_cfg_project'),
               '--quiet',
               ],
  },
  # Configure Siso for developer builds.
  {
    'name': 'configure_siso',
    'pattern': '.',
    'action': ['python3',
               'build/config/siso/configure_siso.py',
               '--rbe_instance',
               Var('rbe_instance'),
               ],
  },
]
