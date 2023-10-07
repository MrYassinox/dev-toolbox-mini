<!-- markdownlint-disable -->

# API Overview

## Modules

- [`utils`](./utils.md#module-utils): Toolbox a mini for devlops. 

## Classes

- [`utils.Argparse`](./utils.md#class-argparse): Argparse - Extended Argument Parser for Command-Line Argument Handling. 
- [`utils.AttrRegisterMap`](./utils.md#class-attrregistermap): A class AttrRegisterMap the attributes register and manages map.
- [`utils.AxisCalc`](./utils.md#class-axiscalc): Calculate the top, bottom, right, and left coordinates of an object based on its axis.
- [`utils.ColorMaterialUi`](./utils.md#class-colormaterialui): A class ColorMaterialUi - The Material UI color names to hex values.
- [`utils.ColorsConstants`](./utils.md#class-colorsconstants): Provide RGB color constants and a colors dictionary with elements formatted. 
- [`utils.ColorsConvartor`](./utils.md#class-colorsconvartor): Color converter class for different color formats.
- [`utils.ExceptionsBase`](./utils.md#class-exceptionsbase): Class that defines variables for built-in exceptions derived from BaseException.
- [`utils.GenerateID`](./utils.md#class-generateid): A class to generate a unique id
- [`utils.KwargsSignature`](./utils.md#class-kwargssignature): A class KwargsSignature the signature provides to keyword, for allows access to keyword by a attributes.
- [`utils.LoggerHandle`](./utils.md#class-loggerhandle): LoggerHandle functionality and exception handling in applications.
- [`utils.Promise`](./utils.md#class-promise): A simplified implementation of promises in Python.
- [`utils.TaskTimer`](./utils.md#class-tasktimer): Task Execution Timer. 
- [`utils.Threaded`](./utils.md#class-threaded): Threaded 

## Functions

- [`utils.check_file_size`](./utils.md#function-check_file_size): Check if the file size is less than or equal to the allowed size.
- [`utils.check_is_matching_pattern`](./utils.md#function-check_is_matching_pattern): Check if any of the patterns match the characters or strings.
- [`utils.check_is_network_available`](./utils.md#function-check_is_network_available): Check if a network connection is available.
- [`utils.check_paths_exist`](./utils.md#function-check_paths_exist): Check the existence of files at specified paths and information about those files.
- [`utils.check_run`](./utils.md#function-check_run): Check if a command runs successfully.
- [`utils.check_signature_object`](./utils.md#function-check_signature_object): introspect function parameters.
- [`utils.check_string_match_pattern`](./utils.md#function-check_string_match_pattern): Check if the characters in the string match the pattern.
- [`utils.checked_instances`](./utils.md#function-checked_instances): Checks the type of the provided object against the specified type checker.
- [`utils.clear`](./utils.md#function-clear): Clear the screen.
- [`utils.closest_supported_dimensions_and_max_pixels`](./utils.md#function-closest_supported_dimensions_and_max_pixels): Resize an shape to the closest supported dimensions and a maximum pixels limit.
- [`utils.create_archive_tar_gz`](./utils.md#function-create_archive_tar_gz): Create a tar.gz archive containing specified files and directories.
- [`utils.create_directory`](./utils.md#function-create_directory): Create a directory.
- [`utils.cv2_to_pillow`](./utils.md#function-cv2_to_pillow): Converts an image from OpenCV to Pillow.
- [`utils.decode_file_bytes`](./utils.md#function-decode_file_bytes): Decode a file encoded with base64.
- [`utils.detect_variable`](./utils.md#function-detect_variable): Detect if the given argument is a function.
- [`utils.dict_to_namespace`](./utils.md#function-dict_to_namespace): Convert a dictionary to a namespace.
- [`utils.edit_file_txt`](./utils.md#function-edit_file_txt): Edit a text file by adding, replacing, or removing content.
- [`utils.encode_file_bytes`](./utils.md#function-encode_file_bytes): Encode a file into base64 and optionally write the encoded data to a file.
- [`utils.format_size_bytes`](./utils.md#function-format_size_bytes): Format a size in bytes into KB, MB, GB, or TB.
- [`utils.generate_seed`](./utils.md#function-generate_seed): Generate a random seed for NumPy or Python's random module.
- [`utils.get_current_py_version`](./utils.md#function-get_current_py_version): Get the current Python version number info.
- [`utils.get_data_from_csv_xlsx`](./utils.md#function-get_data_from_csv_xlsx): Get data from a CSV or XLSX file and return it as a list.
- [`utils.get_file_size`](./utils.md#function-get_file_size): Get the file size in bytes and convert it to bytes, KB, MB, GB, or TB.
- [`utils.get_h_w_c_to_image`](./utils.md#function-get_h_w_c_to_image): Returns the height, width, and number of channels of an image.
- [`utils.get_list_parameter_names_from_fun`](./utils.md#function-get_list_parameter_names_from_fun): Retrieves a list of parameter names from a Python function, method, or class.
- [`utils.get_opencv_formats`](./utils.md#function-get_opencv_formats): Returns a list of available image file formats supported by OpenCV.
- [`utils.get_pillow_formats`](./utils.md#function-get_pillow_formats): Returns a list of available image file formats supported by Pillow.
- [`utils.get_pkg_distribution`](./utils.md#function-get_pkg_distribution): Get the distribution information for a package.
- [`utils.get_py_versions_available`](./utils.md#function-get_py_versions_available): Gets all Python versions available on the system.
- [`utils.get_string_before_pattern`](./utils.md#function-get_string_before_pattern): Get the string before the specified character pattern in the string.
- [`utils.image_to_bytesIO`](./utils.md#function-image_to_bytesio): Convert an image to a BytesIO object.
- [`utils.import_from`](./utils.md#function-import_from): Imports module from a file path. and returns an object from a specified module.
- [`utils.import_lib`](./utils.md#function-import_lib): Imports a module from a file path.
- [`utils.load_image`](./utils.md#function-load_image): Load an image from a file or URL.
- [`utils.measuring_average_color_lightness`](./utils.md#function-measuring_average_color_lightness): Measure the average color lightness based on different methods.
- [`utils.module_exists`](./utils.md#function-module_exists): Check if a module exists.
- [`utils.namespace_to_dict`](./utils.md#function-namespace_to_dict): Convert a namespace to a dictionary.
- [`utils.numpy_to_pillow`](./utils.md#function-numpy_to_pillow): Convert a NumPy array to a PIL.Image.
- [`utils.os_environ_get`](./utils.md#function-os_environ_get): Get the value of an environment variable.
- [`utils.os_environ_list`](./utils.md#function-os_environ_list): Return a list of environment variables.
- [`utils.os_environ_set`](./utils.md#function-os_environ_set): Set an environment variable locally.
- [`utils.pillow_to_cv2`](./utils.md#function-pillow_to_cv2): Converts an image from Pillow to OpenCV.
- [`utils.pillow_to_numpy`](./utils.md#function-pillow_to_numpy): Converts a Pillow image object to a NumPy array.
- [`utils.platform_system_detect`](./utils.md#function-platform_system_detect): Detects the current platform or operating system.
- [`utils.read_pillow_from_array`](./utils.md#function-read_pillow_from_array): Creates a Pillow image object from the specified NumPy array.
- [`utils.read_with_opencv`](./utils.md#function-read_with_opencv): Reads an image from the specified file path using OpenCV and returns it as a NumPy array.
- [`utils.read_with_pillow`](./utils.md#function-read_with_pillow): Reads an image from the specified file path using Pillow and returns it as a NumPy array.
- [`utils.reads_csvfile`](./utils.md#function-reads_csvfile): Read a CSV file and extract specified columns data.
- [`utils.remove_files_older`](./utils.md#function-remove_files_older): Remove files that are older than specified days.
- [`utils.repositories`](./utils.md#function-repositories): Manage repositories.
- [`utils.requests_get`](./utils.md#function-requests_get): Download a file using requests.
- [`utils.resize_image_to_closest_dimension`](./utils.md#function-resize_image_to_closest_dimension): Resizing an image to the closest supported dimension specified in a list.
- [`utils.resize_image_to_closest_max_pixels`](./utils.md#function-resize_image_to_closest_max_pixels): Resize an image to the closest supported dimensions of pixels that exceed a maximum limit.
- [`utils.retrieves_image_from_dir`](./utils.md#function-retrieves_image_from_dir): Retrieves image names or paths from a directory.
- [`utils.retrieves_modules_from_dir`](./utils.md#function-retrieves_modules_from_dir): Retrieves classes and/or functions from modules in a directory.
- [`utils.run_python`](./utils.md#function-run_python): Run a Python command and capture the output.
- [`utils.run_shell_command`](./utils.md#function-run_shell_command): Run a shell command python and capture the output.
- [`utils.safe_exception_execute`](./utils.md#function-safe_exception_execute): Executes a target function or action safely, catching specified exceptions and returning a default value or the exception itself.
- [`utils.search_and_edite_module`](./utils.md#function-search_and_edite_module): Searches for a specified content in a module file and replaces it with new content.
- [`utils.search_and_replace`](./utils.md#function-search_and_replace): Search for a word in a file and optionally replace it with a new word.
- [`utils.search_scanne_folder`](./utils.md#function-search_scanne_folder): Scan a folder and return the list of files and other relevant information.
- [`utils.search_str`](./utils.md#function-search_str): Search for a word in a file and print if it exists or not.
- [`utils.search_str_by_line`](./utils.md#function-search_str_by_line): Search for a word in each line of a file and print the line and line number if found.
- [`utils.setup_temp`](./utils.md#function-setup_temp): Initialize a temporary folder path.
- [`utils.split_file_path`](./utils.md#function-split_file_path): Splits a file path into its directory name, base name, and extension.
- [`utils.store_img_binary`](./utils.md#function-store_img_binary): Store images in binary PIL mode.
- [`utils.store_metadata_png`](./utils.md#function-store_metadata_png): Store metadata in a PNG image.
- [`utils.strTobool`](./utils.md#function-strtobool): Convert a string representation to an actual boolean value.
- [`utils.sub_gitclone`](./utils.md#function-sub_gitclone): Clone a Git repository from a given URL.
- [`utils.sub_gitinstall`](./utils.md#function-sub_gitinstall): Install a Git module.
- [`utils.sub_run`](./utils.md#function-sub_run): Run a subprocess command and capture the output.
- [`utils.sub_wget`](./utils.md#function-sub_wget): Download a file using wget.
- [`utils.temporary_file`](./utils.md#function-temporary_file): Create a temporary file and write the bytes data to it.
- [`utils.threading_manager_functions`](./utils.md#function-threading_manager_functions): Manage threading operations by creating and returning either a Thread or a Timer object.
- [`utils.time_sleep_accuracy`](./utils.md#function-time_sleep_accuracy): The time sleep duration with higher accuracy.
- [`utils.utils_image`](./utils.md#function-utils_image): Utility for image processing.
- [`utils.wget`](./utils.md#function-wget): Download a file using wget.
- [`utils.wrapper_decorator`](./utils.md#function-wrapper_decorator): Decorator sample.
- [`utils.wrapper_decorator_threaded`](./utils.md#function-wrapper_decorator_threaded): Decorator to create threaded functions.
- [`utils.wrapper_decorator_timetask`](./utils.md#function-wrapper_decorator_timetask): Decorator function to measure the execution time of a given function.
- [`utils.writes_csvfile`](./utils.md#function-writes_csvfile): Writes data to a CSV file.
