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

  'abseil_revision': '0b76dfe4fffd3f49efacde5f3268b02f9c060ef0',
  'abseil_url': 'https://chromium.googlesource.com/chromium/src/third_party/abseil-cpp.git',

  'build_revision': 'dc8b2298602e358156f40e1c5531c7c8c3d27c93',
  'build_url': 'https://chromium.googlesource.com/chromium/src/build.git',

  'buildtools_revision': 'f312f0fbb3030c07a57524691e03aa1cd14f3d02',
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

  'clang_revision': 'ec29fe1f187bfc6e995a7a602f77d31226817d17',
  'clang_url': 'https://chromium.googlesource.com/chromium/src/tools/clang.git',

  'depot_tools_revision': 'ba733f35cde8ae85e7ca85956cdc63b297dc9425',
  'depot_tools_url': 'https://chromium.googlesource.com/chromium/tools/depot_tools.git',

  # Fetch configuration files required for the 'use_remoteexec' gn arg
  'download_remoteexec_cfg': False,

  # GN CIPD package version.
  'gn_version': 'git_revision:e9e83d9095d3234adf68f3e2866f25daf766d5c7',

  # ninja CIPD package version.
  # https://chrome-infra-packages.appspot.com/p/infra/3pp/tools/ninja
  'ninja_version': 'version:2@1.11.1.chromium.6',

  'fast_float_revision': 'd7417618f93d2c47e9bbde561510f9fc8bafe003',
  'fast_float_url': 'https://chromium.googlesource.com/external/github.com/fastfloat/fast_float.git',

  'fp16_revision': '98b0a46bce017382a6351a19577ec43a715b6835',
  'fp16_url': 'https://chromium.googlesource.com/external/github.com/Maratyszcza/FP16.git',

  'googletest_revision': '35d0c365609296fa4730d62057c487e3cfa030ff',
  'googletest_url': 'https://chromium.googlesource.com/external/github.com/google/googletest.git',

  'highway_revision': '00fe003dac355b979f36157f9407c7c46448958e',
  'highway_url': 'https://chromium.googlesource.com/external/github.com/google/highway.git',

  'icu_revision': 'ba7ed88cc5ffa428a82a0f787dd61031aa5ef4ca',
  'icu_url': 'https://chromium.googlesource.com/chromium/deps/icu.git',

  'jinja2_revision': '5e1ee241ab04b38889f8d517f2da8b3df7cfbd9a',
  'jinja2_url': 'https://chromium.googlesource.com/chromium/src/third_party/jinja2.git',

  'markupsafe_revision': '9f8efc8637f847ab1ba984212598e6fb9cf1b3d4',
  'markupsafe_url': 'https://chromium.googlesource.com/chromium/src/third_party/markupsafe.git',

  'node_revision': '47e20948977075562fc96f8e1e87ac3d9f26ee72',
  'node_url': 'https://chromium.googlesource.com/external/github.com/v8/node.git',

  'trace_common_revision' : '148c806f46c0f8d2e5e888a8175b656ad4cfee43',
  'trace_common_url': 'https://chromium.googlesource.com/chromium/src/base/trace_event/common.git',

  'v8_revision': 'd7d1b12a6e2f83038c18914084cff426f1969839',
  'v8_url': 'https://chromium.googlesource.com/v8/v8.git',

  'zlib_revision': '82a5fecf8aae8f288267cfdb2d29c9ebf7b37e59',
  'zlib_url': 'https://chromium.googlesource.com/chromium/src/third_party/zlib.git',

  'reclient_version': 're_client_version:0.105.0.d6a0caf-gomaip',

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
  'third_party/clang-format/script': Var('buildtools_clang_format_url') + '@' + Var('buildtools_clang_format_revision'),
  'third_party/libc++/src': Var('buildtools_libcxx_url') + '@' + Var('buildtools_libcxx_revision'),
  'third_party/libc++abi/src': Var('buildtools_libcxxabi_url') + '@' + Var('buildtools_libcxxabi_revision'),
  'third_party/llvm-libc/src': Var('buildtools_llvm_libc_url') + '@' + Var('buildtools_llvm_libc_revision'),
  'third_party/libunwind/src': Var('buildtools_libunwind_url') + '@' + Var('buildtools_libunwind_revision'),
  'node': Var('node_url') + '@' + Var('node_revision'),
  'third_party/abseil-cpp': Var('abseil_url') + '@' + Var('abseil_revision'),
  'third_party/depot_tools': Var('depot_tools_url') + '@' + Var('depot_tools_revision'),
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
]
