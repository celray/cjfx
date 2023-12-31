This module helps ease annoying small tasks especially for data scientists. It has the following main functionalities.

## cjfx.excel

- This module will create an excel file with much ease. You can to rows, columns or target cells, write formulas add sheets and add charts to your excel book. It does not modefy existing ones.

## cjfx.word_document

- This will help you create word documents including adding figures and basic formating.

## cjfx.mssql_cinnection

- An easy to use abstraction layer for pyodbc in conjuction with pandas and geopandas to manage MSSQL databases.

## cjfx.sqlite_connection

- An abstraction layer for sqlite3 for quick management of sqlite databases.

## functions that you didn't know you needed

    write_to(filepath:str, string_to_write:str) -> writes a string to file on disk
    read_from(filepath:str) -> reads from an asci file on disk
    exists(path) -> checks if a path exists returns a boolean.
    file_name(file_path:str) -> gives you the file basename (with option to include file extension).
    list_files(dir_path:str) -> lists all files in a given directory with option to filter by extension. returns a list of paths
    list_all_files(dir_path:str) -> same as 'list_files' but includes subfolders.
    list_folders(dir_path:str) -> lists all directories in a given folder. returns a list of folder names.
    python_variable -> a quick funtion to save or load a python variable to disk.
    show_progress -> shows a progress bar for long loops.

## other functions

        copy_file,
        ignore_warnings,
        transparent_image,
        get_file_size,
        merge_documents,
        resize_image,
        download_file,
        get_nse,
        get_pbias,
        delete_path,
        save_array_as_image,
        create_icon,
        unzip_file,

        this_dir,
        copy_projection,
        set_tif_nodata,
        clip_features,
        assign_default_projection,
        plot,
        show,
        copy_directory_tree,
        remove_header_duplicates,
        get_swat_timeseries,
        clip_raster,
        points_to_geodataframe,
        convert_webm_to_mp3,
        download_video_youtube,
        get_relative_path,
        install_package,
        get_usgs_timeseries,
        decode_64,
        wait,
        get_raster_value_for_coords,
        rasterise_shape,
        extract_timeseries_from_netcdf,
        rand_apha_num,
        make_plot,
        goto_dir,
        smart_copy,
        print_dict,
        cd,
        slope_intercept,
        distance,
        download_file2,
        xml_children_attributes,
        report,
        print_list,
        disp,
        create_path,
        flow_duration_curve,
        is_file,
        resample_ts_df,
        raster_statistics,
        empty_line,
        hide_folder,
        time_stamp,
        copy_folder,
        delete_file,
        run_swat_plus,
        open_file_in_code,
        format_timedelta,
        confirm,
        open_tif_as_array,
        single_spaces,
        view,
        quit,
        insert_newlines,
        gdal_datatypes,
        resample_raster,
        create_polygon_geodataframe,
        reproject_raster,
        set_nodata,
        get_extents,
        error,
        strip_characters,
