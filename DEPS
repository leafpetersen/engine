# This file is automatically processed to create .DEPS.git which is the file
# that gclient uses under git.
#
# See http://code.google.com/p/chromium/wiki/UsingGit
#
# To test manually, run:
#   python tools/deps2git/deps2git.py -o .DEPS.git -w <gclientdir>
# where <gcliendir> is the absolute path to the directory containing the
# .gclient file (the parent of 'src').
#
# Then commit .DEPS.git locally (gclient doesn't like dirty trees) and run
#   gclient sync..
# Verify the thing happened you wanted. Then revert your .DEPS.git change
# DO NOT CHECK IN CHANGES TO .DEPS.git upstream. It will be automatically
# updated by a bot when you modify this one.
#
# When adding a new dependency, please update the top-level .gitignore file
# to list the dependency's destination directory.

vars = {
  'chromium_git': 'https://chromium.googlesource.com',
  'swiftshader_git': 'https://swiftshader.googlesource.com',
  'dart_git': 'https://dart.googlesource.com',
  'fuchsia_git': 'https://fuchsia.googlesource.com',
  'github_git': 'https://github.com',
  'skia_git': 'https://skia.googlesource.com',
  # OCMock is for testing only so there is no google clone
  'ocmock_git': 'https://github.com/erikdoe/ocmock.git',
  'skia_revision': 'b14b1444588430186ed4d56270fa4d5c3399ec50',

  # When updating the Dart revision, ensure that all entries that are
  # dependencies of Dart are also updated to match the entries in the
  # Dart SDK's DEPS file for that revision of Dart. The DEPS file for
  # Dart is: https://github.com/dart-lang/sdk/blob/master/DEPS.
  # You can use //tools/dart/create_updated_flutter_deps.py to produce
  # updated revision list of existing dependencies.
  'dart_revision': 'b85c68a73cc2bed3d62999d36707c1006f555b11',

  # WARNING: DO NOT EDIT MANUALLY
  # The lines between blank lines above and below are generated by a script. See create_updated_flutter_deps.py
  'dart_args_tag': '1.6.0',
  'dart_async_tag': '2.4.1',
  'dart_bazel_worker_tag': 'v0.1.22',
  'dart_boolean_selector_tag': '1.0.4',
  'dart_boringssl_gen_rev': 'b9e27cff1ff0803e97ab1f88764a83be4aa94a6d',
  'dart_boringssl_rev': '4dfd5af70191b068aebe567b8e29ce108cee85ce',
  'dart_charcode_tag': 'v1.1.2',
  'dart_cli_util_rev': '4ad7ccbe3195fd2583b30f86a86697ef61e80f41',
  'dart_collection_tag': '1.14.11',
  'dart_convert_tag': '2.0.2',
  'dart_crypto_tag': '2.0.6',
  'dart_csslib_tag': '0.15.0',
  'dart_dart2js_info_tag': '0.6.0',
  'dart_dart_style_tag': '1.3.2',
  'dart_ffi_tag': 'ea88d71b043ee14b268c3aedff14e9eb32e20959',
  'dart_fixnum_tag': '0.10.9',
  'dart_glob_tag': '1.1.7',
  'dart_html_tag': '0.14.0+1',
  'dart_http_parser_tag': '3.1.3',
  'dart_http_retry_tag': '0.1.1',
  'dart_http_tag': '0.12.0+2',
  'dart_http_throttle_tag': '1.0.2',
  'dart_intl_tag': '0.16.1',
  'dart_json_rpc_2_tag': '2.0.9',
  'dart_linter_tag': '0.1.114',
  'dart_logging_tag': '0.11.3+2',
  'dart_markdown_tag': '2.1.1',
  'dart_matcher_tag': '0.12.5',
  'dart_mime_tag': '0.9.6+2',
  'dart_mockito_tag': 'd39ac507483b9891165e422ec98d9fb480037c8b',
  'dart_mustache_tag': '5e81b12215566dbe2473b2afd01a8a8aedd56ad9',
  'dart_oauth2_tag': '1.2.1',
  'dart_observatory_pub_packages_rev': '0894122173b0f98eb08863a7712e78407d4477bc',
  'dart_package_config_tag': 'v1.9.2',
  'dart_path_tag': '1.6.2',
  'dart_pedantic_tag': 'v1.8.0',
  'dart_pool_tag': '1.3.6',
  'dart_protobuf_rev': '3746c8fd3f2b0147623a8e3db89c3ff4330de760',
  'dart_pub_rev': '978cc9c4be7d8978348e56d4ae82be8257a59579',
  'dart_pub_semver_tag': 'v1.4.4',
  'dart_quiver-dart_tag': '2.0.0+1',
  'dart_resource_rev': 'f8e37558a1c4f54550aa463b88a6a831e3e33cd6',
  'dart_root_certificates_rev': '16ef64be64c7dfdff2b9f4b910726e635ccc519e',
  'dart_shelf_packages_handler_tag': '2.0.0',
  'dart_shelf_static_rev': 'v0.2.8',
  'dart_shelf_tag': '0.7.3+3',
  'dart_shelf_web_socket_tag': '0.2.2+3',
  'dart_source_map_stack_trace_tag': '2.0.0',
  'dart_source_maps_tag': '8af7cc1a1c3a193c1fba5993ce22a546a319c40e',
  'dart_source_span_tag': '1.7.0',
  'dart_stack_trace_tag': '1.9.3',
  'dart_stagehand_tag': 'v3.3.7',
  'dart_stream_channel_tag': '2.0.0',
  'dart_string_scanner_tag': '1.0.3',
  'dart_term_glyph_tag': '1.0.1',
  'dart_test_reflective_loader_tag': '0.1.9',
  'dart_test_tag': 'test_core-v0.3.2',
  'dart_tflite_native_rev': '3c777c40608a2a9f1427bfe0028ab48e7116b4c1',
  'dart_typed_data_tag': '1.1.6',
  'dart_usage_tag': '3.4.0',
  'dart_watcher_rev': '0.9.7+14',
  'dart_web_socket_channel_tag': '1.0.15',
  'dart_yaml_tag': '2.2.0',

  'ocmock_tag': 'v3.4.3',

  # Build bot tooling for iOS
  'ios_tools_revision': '69b7c1b160e7107a6a98d948363772dc9caea46f',

  # Checkout Android dependencies only on platforms where we build for Android targets.
  'download_android_deps': 'host_os == "mac" or host_os == "linux"',

  # Checkout Windows dependencies only if we are building on Windows.
  'download_windows_deps' : 'host_os == "win"',

  # An LLVM backend needs LLVM binaries and headers. To avoid build time
  # increases we can use prebuilts. We don't want to download this on every
  # CQ/CI bot nor do we want the average Dart developer to incur that cost.
  # So by default we will not download prebuilts. This varible is needed in
  # the flutter engine to ensure that Dart gn has access to it as well.
  "checkout_llvm": False,
}

gclient_gn_args_file = 'src/third_party/dart/build/config/gclient_args.gni'
gclient_gn_args = [
  'checkout_llvm'
]

# Only these hosts are allowed for dependencies in this DEPS file.
# If you need to add a new host, contact chrome infrastructure team.
allowed_hosts = [
  'chromium.googlesource.com',
  'fuchsia.googlesource.com',
  'github.com',
  'skia.googlesource.com',
]

deps = {
  'src': 'https://github.com/flutter/buildroot.git' + '@' + 'a0fb98af7b6f50f17b47ab7968f3f5664d0d6316',

   # Fuchsia compatibility
   #
   # The dependencies in this section should match the layout in the Fuchsia gn
   # build. Eventually, we'll manage these dependencies together with Fuchsia
   # and not have to specific specific hashes.

  'src/third_party/benchmark':
   Var('fuchsia_git') + '/third_party/benchmark' + '@' + 'a779ffce872b4c811beef482e18bd0b63626aa42',

  'src/third_party/googletest':
   Var('fuchsia_git') + '/third_party/googletest' + '@' + '3fef9015bfe7617d57806cd7c73a653b28559fae',

  'src/third_party/rapidjson':
   Var('fuchsia_git') + '/third_party/rapidjson' + '@' + 'ef3564c5c8824989393b87df25355baf35ff544b',

  'src/third_party/harfbuzz':
   Var('fuchsia_git') + '/third_party/harfbuzz' + '@' + 'f5c000538699a4e40649508a44f41d37035e6c35',

  'src/third_party/libcxx':
   Var('fuchsia_git') + '/third_party/libcxx' + '@' + '7524ef50093a376f334a62a7e5cebf5d238d4c99',

  'src/third_party/libcxxabi':
   Var('fuchsia_git') + '/third_party/libcxxabi' + '@' + '74d1e602c76350f0760bf6907910e4f3a4fccffe',

  'src/third_party/glfw':
   Var('fuchsia_git') + '/third_party/glfw' + '@' + '999f3556fdd80983b10051746264489f2cb1ef16',

   # Chromium-style
   #
   # As part of integrating with Fuchsia, we should eventually remove all these
   # Chromium-style dependencies.

  'src/ios_tools':
   Var('chromium_git') + '/chromium/src/ios.git' + '@' + Var('ios_tools_revision'),

  'src/third_party/icu':
   Var('chromium_git') + '/chromium/deps/icu.git' + '@' + '5005010d694e16571b8dfbf07d70817841f80a69',

  'src/third_party/boringssl':
   Var('github_git') + '/dart-lang/boringssl_gen.git' + '@' + Var('dart_boringssl_gen_rev'),

  'src/third_party/boringssl/src':
   'https://boringssl.googlesource.com/boringssl.git' + '@' + Var('dart_boringssl_rev'),

  'src/third_party/dart':
   Var('dart_git') + '/sdk.git' + '@' + Var('dart_revision'),

  # WARNING: Unused Dart dependencies in the list below till "WARNING:" marker are removed automatically - see create_updated_flutter_deps.py.

  'src/third_party/dart/pkg/analysis_server/language_model':
   {'packages': [{'version': 'lIRt14qoA1Cocb8j3yw_Fx5cfYou2ddam6ArBm4AI6QC', 'package': 'dart/language_model'}], 'dep_type': 'cipd'},

  'src/third_party/dart/third_party/observatory_pub_packages':
   Var('dart_git') + '/observatory_pub_packages.git' + '@' + Var('dart_observatory_pub_packages_rev'),

  'src/third_party/dart/third_party/pkg/args':
   Var('dart_git') + '/args.git' + '@' + Var('dart_args_tag'),

  'src/third_party/dart/third_party/pkg/async':
   Var('dart_git') + '/async.git' + '@' + Var('dart_async_tag'),

  'src/third_party/dart/third_party/pkg/bazel_worker':
   Var('dart_git') + '/bazel_worker.git' + '@' + Var('dart_bazel_worker_tag'),

  'src/third_party/dart/third_party/pkg/boolean_selector':
   Var('dart_git') + '/boolean_selector.git' + '@' + Var('dart_boolean_selector_tag'),

  'src/third_party/dart/third_party/pkg/charcode':
   Var('dart_git') + '/charcode.git' + '@' + Var('dart_charcode_tag'),

  'src/third_party/dart/third_party/pkg/cli_util':
   Var('dart_git') + '/cli_util.git' + '@' + Var('dart_cli_util_rev'),

  'src/third_party/dart/third_party/pkg/collection':
   Var('dart_git') + '/collection.git' + '@' + Var('dart_collection_tag'),

  'src/third_party/dart/third_party/pkg/convert':
   Var('dart_git') + '/convert.git' + '@' + Var('dart_convert_tag'),

  'src/third_party/dart/third_party/pkg/crypto':
   Var('dart_git') + '/crypto.git' + '@' + Var('dart_crypto_tag'),

  'src/third_party/dart/third_party/pkg/csslib':
   Var('dart_git') + '/csslib.git' + '@' + Var('dart_csslib_tag'),

  'src/third_party/dart/third_party/pkg/dart2js_info':
   Var('dart_git') + '/dart2js_info.git' + '@' + Var('dart_dart2js_info_tag'),

  'src/third_party/dart/third_party/pkg/dartdoc':
   Var('dart_git') + '/dartdoc.git@v0.30.3',

  'src/third_party/dart/third_party/pkg/ffi':
   Var('dart_git') + '/ffi.git' + '@' + Var('dart_ffi_tag'),

  'src/third_party/dart/third_party/pkg/fixnum':
   Var('dart_git') + '/fixnum.git' + '@' + Var('dart_fixnum_tag'),

  'src/third_party/dart/third_party/pkg/glob':
   Var('dart_git') + '/glob.git' + '@' + Var('dart_glob_tag'),

  'src/third_party/dart/third_party/pkg/html':
   Var('dart_git') + '/html.git' + '@' + Var('dart_html_tag'),

  'src/third_party/dart/third_party/pkg/http':
   Var('dart_git') + '/http.git' + '@' + Var('dart_http_tag'),

  'src/third_party/dart/third_party/pkg/http_multi_server':
   Var('dart_git') + '/http_multi_server.git@ea269f79321d659208402088f3297e8920a88ee6',

  'src/third_party/dart/third_party/pkg/http_parser':
   Var('dart_git') + '/http_parser.git' + '@' + Var('dart_http_parser_tag'),

  'src/third_party/dart/third_party/pkg/http_retry':
   Var('dart_git') + '/http_retry.git' + '@' + Var('dart_http_retry_tag'),

  'src/third_party/dart/third_party/pkg/http_throttle':
   Var('dart_git') + '/http_throttle.git' + '@' + Var('dart_http_throttle_tag'),

  'src/third_party/dart/third_party/pkg/intl':
   Var('dart_git') + '/intl.git' + '@' + Var('dart_intl_tag'),

  'src/third_party/dart/third_party/pkg/json_rpc_2':
   Var('dart_git') + '/json_rpc_2.git' + '@' + Var('dart_json_rpc_2_tag'),

  'src/third_party/dart/third_party/pkg/linter':
   Var('dart_git') + '/linter.git' + '@' + Var('dart_linter_tag'),

  'src/third_party/dart/third_party/pkg/logging':
   Var('dart_git') + '/logging.git' + '@' + Var('dart_logging_tag'),

  'src/third_party/dart/third_party/pkg/markdown':
   Var('dart_git') + '/markdown.git' + '@' + Var('dart_markdown_tag'),

  'src/third_party/dart/third_party/pkg/matcher':
   Var('dart_git') + '/matcher.git' + '@' + Var('dart_matcher_tag'),

  'src/third_party/dart/third_party/pkg/mime':
   Var('dart_git') + '/mime.git' + '@' + Var('dart_mime_tag'),

  'src/third_party/dart/third_party/pkg/mockito':
   Var('dart_git') + '/mockito.git' + '@' + Var('dart_mockito_tag'),

  'src/third_party/dart/third_party/pkg/mustache':
   Var('dart_git') + '/external/github.com/xxgreg/mustache' + '@' + Var('dart_mustache_tag'),

  'src/third_party/dart/third_party/pkg/oauth2':
   Var('dart_git') + '/oauth2.git' + '@' + Var('dart_oauth2_tag'),

  'src/third_party/dart/third_party/pkg/path':
   Var('dart_git') + '/path.git' + '@' + Var('dart_path_tag'),

  'src/third_party/dart/third_party/pkg/pedantic':
   Var('dart_git') + '/pedantic.git' + '@' + Var('dart_pedantic_tag'),

  'src/third_party/dart/third_party/pkg/pool':
   Var('dart_git') + '/pool.git' + '@' + Var('dart_pool_tag'),

  'src/third_party/dart/third_party/pkg/protobuf':
   Var('dart_git') + '/protobuf.git' + '@' + Var('dart_protobuf_rev'),

  'src/third_party/dart/third_party/pkg/pub':
   Var('dart_git') + '/pub.git' + '@' + Var('dart_pub_rev'),

  'src/third_party/dart/third_party/pkg/pub_semver':
   Var('dart_git') + '/pub_semver.git' + '@' + Var('dart_pub_semver_tag'),

  'src/third_party/dart/third_party/pkg/quiver':
   Var('chromium_git') + '/external/github.com/google/quiver-dart.git' + '@' + Var('dart_quiver-dart_tag'),

  'src/third_party/dart/third_party/pkg/resource':
   Var('dart_git') + '/resource.git' + '@' + Var('dart_resource_rev'),

  'src/third_party/dart/third_party/pkg/shelf':
   Var('dart_git') + '/shelf.git' + '@' + Var('dart_shelf_tag'),

  'src/third_party/dart/third_party/pkg/shelf_packages_handler':
   Var('dart_git') + '/shelf_packages_handler.git' + '@' + Var('dart_shelf_packages_handler_tag'),

  'src/third_party/dart/third_party/pkg/shelf_static':
   Var('dart_git') + '/shelf_static.git' + '@' + Var('dart_shelf_static_rev'),

  'src/third_party/dart/third_party/pkg/shelf_web_socket':
   Var('dart_git') + '/shelf_web_socket.git' + '@' + Var('dart_shelf_web_socket_tag'),

  'src/third_party/dart/third_party/pkg/source_map_stack_trace':
   Var('dart_git') + '/source_map_stack_trace.git' + '@' + Var('dart_source_map_stack_trace_tag'),

  'src/third_party/dart/third_party/pkg/source_maps':
   Var('dart_git') + '/source_maps.git' + '@' + Var('dart_source_maps_tag'),

  'src/third_party/dart/third_party/pkg/source_span':
   Var('dart_git') + '/source_span.git' + '@' + Var('dart_source_span_tag'),

  'src/third_party/dart/third_party/pkg/stack_trace':
   Var('dart_git') + '/stack_trace.git' + '@' + Var('dart_stack_trace_tag'),

  'src/third_party/dart/third_party/pkg/stagehand':
   Var('dart_git') + '/stagehand.git' + '@' + Var('dart_stagehand_tag'),

  'src/third_party/dart/third_party/pkg/stream_channel':
   Var('dart_git') + '/stream_channel.git' + '@' + Var('dart_stream_channel_tag'),

  'src/third_party/dart/third_party/pkg/string_scanner':
   Var('dart_git') + '/string_scanner.git' + '@' + Var('dart_string_scanner_tag'),

  'src/third_party/dart/third_party/pkg/term_glyph':
   Var('dart_git') + '/term_glyph.git' + '@' + Var('dart_term_glyph_tag'),

  'src/third_party/dart/third_party/pkg/test':
   Var('dart_git') + '/test.git' + '@' + Var('dart_test_tag'),

  'src/third_party/dart/third_party/pkg/test_reflective_loader':
   Var('dart_git') + '/test_reflective_loader.git' + '@' + Var('dart_test_reflective_loader_tag'),

  'src/third_party/dart/third_party/pkg/tflite_native':
   Var('dart_git') + '/tflite_native.git' + '@' + Var('dart_tflite_native_rev'),

  'src/third_party/dart/third_party/pkg/typed_data':
   Var('dart_git') + '/typed_data.git' + '@' + Var('dart_typed_data_tag'),

  'src/third_party/dart/third_party/pkg/usage':
   Var('dart_git') + '/usage.git' + '@' + Var('dart_usage_tag'),

  'src/third_party/dart/third_party/pkg/watcher':
   Var('dart_git') + '/watcher.git' + '@' + Var('dart_watcher_rev'),

  'src/third_party/dart/third_party/pkg/web_socket_channel':
   Var('dart_git') + '/web_socket_channel.git' + '@' + Var('dart_web_socket_channel_tag'),

  'src/third_party/dart/third_party/pkg/yaml':
   Var('dart_git') + '/yaml.git' + '@' + Var('dart_yaml_tag'),

  'src/third_party/dart/third_party/pkg_tested/dart_style':
   Var('dart_git') + '/dart_style.git' + '@' + Var('dart_dart_style_tag'),

  'src/third_party/dart/third_party/pkg_tested/package_config':
   Var('dart_git') + '/package_config.git' + '@' + Var('dart_package_config_tag'),

  'src/third_party/dart/tools/sdks':
   {'packages': [{'version': 'version:2.8.0-dev.18.0', 'package': 'dart/dart-sdk/${{platform}}'}], 'dep_type': 'cipd'},

  # WARNING: end of dart dependencies list that is cleaned up automatically - see create_updated_flutter_deps.py.

  'src/third_party/colorama/src':
   Var('chromium_git') + '/external/colorama.git' + '@' + '799604a1041e9b3bc5d2789ecbd7e8db2e18e6b8',

  'src/third_party/freetype2':
   Var('fuchsia_git') + '/third_party/freetype2' + '@' + 'edab12c07ac05d1185616688f338b1ad15936796',

  'src/third_party/root_certificates':
   Var('dart_git') + '/root_certificates.git' + '@' + Var('dart_root_certificates_rev'),

  'src/third_party/skia':
   Var('skia_git') + '/skia.git' + '@' +  Var('skia_revision'),

  'src/third_party/ocmock':
   Var('ocmock_git') + '@' +  Var('ocmock_tag'),

  'src/third_party/libjpeg-turbo':
   Var('fuchsia_git') + '/third_party/libjpeg-turbo' + '@' + '0fb821f3b2e570b2783a94ccd9a2fb1f4916ae9f',

  'src/third_party/libwebp':
   Var('chromium_git') + '/webm/libwebp.git' + '@' + '0.6.0',

  'src/third_party/wuffs':
   Var('skia_git') + '/external/github.com/google/wuffs.git' + '@' +  '4080840928c0b05a80cda0d14ac2e2615f679f1a',

  'src/third_party/fontconfig/src':
   Var('chromium_git') + '/external/fontconfig.git' + '@' + 'c336b8471877371f0190ba06f7547c54e2b890ba',

  'src/third_party/gyp':
   Var('chromium_git') + '/external/gyp.git' + '@' + '4801a5331ae62da9769a327f11c4213d32fb0dad',

   # Headers for Vulkan 1.1
   'src/third_party/vulkan':
   Var('github_git') + '/KhronosGroup/Vulkan-Docs.git' + '@' + 'v1.1.91',

   'src/third_party/swiftshader':
   Var('swiftshader_git') + '/SwiftShader.git' + '@' + '5d1e8540407c138f47028d64684f3da599430aa4',

   'src/third_party/angle':
   Var('github_git') + '/google/angle.git' + '@' + '3ea90d609720b7b9b9d05ca094860382f2425294',

  'src/third_party/pkg/when':
   Var('dart_git') + '/when.git' + '@' + '0.2.0',

   'src/third_party/android_tools/ndk': {
     'packages': [
       {
        'package': 'flutter/android/ndk/${{platform}}',
        'version': 'version:r19b'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

   'src/third_party/android_tools/google-java-format': {
     'packages': [
       {
        'package': 'flutter/android/google-java-format',
        'version': 'version:1.7-1'
       }
     ],
     # We want to be able to format these as part of CI, and the CI step that
     # checks formatting runs without downloading the rest of the Android build
     # tooling. Therefore unlike all the other Android-related tools, we want to
     # download this every time.
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/build-tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/build-tools/${{platform}}',
        'version': 'version:29.0.1'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/platform-tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/platform-tools/${{platform}}',
        'version': 'version:29.0.2'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/platforms': {
     'packages': [
       {
        'package': 'flutter/android/sdk/platforms',
        'version': 'version:29r1'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/tools/${{platform}}',
        'version': 'version:26.1.1'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_embedding_dependencies': {
     'packages': [
       {
        'package': 'flutter/android/embedding_bundle',
        'version': 'last_updated:2020-03-13T15:42:26-0700'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/flutter/third_party/gn': {
    'packages': [
      {
        'package': 'gn/gn/${{platform}}',
        'version': 'git_revision:152c5144ceed9592c20f0c8fd55769646077569b'
      },
    ],
    'dep_type': 'cipd',
  },

  'src/buildtools/{host_os}-x64/clang': {
    'packages': [
      {
        'package': 'fuchsia/clang/${{platform}}',
        'version': 'git_revision:de39621f0f03f20633bdfa50bde97a3908bf6e98'
      }
    ],
    'condition': 'host_os == "mac" or host_os == "linux"',
    'dep_type': 'cipd',
  },

   # Get the SDK from https://chrome-infra-packages.appspot.com/p/fuchsia/sdk/core at the 'latest' tag
   # Get the toolchain from https://chrome-infra-packages.appspot.com/p/fuchsia/clang at the 'goma' tag

   'src/fuchsia/sdk/mac': {
     'packages': [
       {
        'package': 'fuchsia/sdk/core/mac-amd64',
        'version': 'QgqO4GD9LyzxC2YeQRVtcEcAmWeTSE60_ikGNyIhJocC'
       }
     ],
     'condition': 'host_os == "mac"',
     'dep_type': 'cipd',
   },
   'src/fuchsia/toolchain/mac': {
     'packages': [
       {
        'package': 'fuchsia/clang/mac-amd64',
        'version': 'OzTZOKkICT0yD82Dbx0jvVn5hN5eOSi6ByVTDseE7i0C'
       }
     ],
     'condition': 'host_os == "mac"',
     'dep_type': 'cipd',
   },
   'src/fuchsia/sdk/linux': {
     'packages': [
       {
        'package': 'fuchsia/sdk/core/linux-amd64',
        'version': 'zJlvoar3sx4OYVmudzR5YziSAeREtThZuCyVjSL3SkYC'
       }
     ],
     'condition': 'host_os == "linux"',
     'dep_type': 'cipd',
   },
   'src/fuchsia/toolchain/linux': {
     'packages': [
       {
        'package': 'fuchsia/clang/linux-amd64',
        'version': 'OT6p30bQQhyCzRSy7xPsSbZ88J3PWOnneenkMZ0j7kIC'
       }
     ],
     'condition': 'host_os == "linux"',
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
        'python',
        'src/build/landmines.py',
    ],
  },
  {
    # Update the Windows toolchain if necessary.
    'name': 'win_toolchain',
    'condition': 'download_windows_deps',
    'pattern': '.',
    'action': ['python', 'src/build/vs_toolchain.py', 'update'],
  },
  {
    'name': 'generate_package_files',
    'pattern': '.',
    'cwd': 'src/',
    'action': ['python', 'flutter/tools/generate_package_files.py'],
  },
  {
    # Ensure that we don't accidentally reference any .pyc files whose
    # corresponding .py files have already been deleted.
    'name': 'remove_stale_pyc_files',
    'pattern': 'src/tools/.*\\.py',
    'action': [
        'python',
        'src/tools/remove_stale_pyc_files.py',
        'src/tools',
    ],
  },
  {
    'name': '7zip',
    'pattern': '.',
    'condition': 'download_windows_deps',
    'action': [
      'download_from_google_storage',
      '--no_auth',
      '--no_resume',
      '--bucket',
      'dart-dependencies',
      '--platform=win32',
      '--extract',
      '-s',
      'src/third_party/dart/third_party/7zip.tar.gz.sha1',
    ],
  },
]
