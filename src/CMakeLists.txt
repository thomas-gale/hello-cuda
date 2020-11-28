add_executable(hellocuda
    Main.cu)

set_target_properties(hellocuda
                       PROPERTIES CUDA_SEPARABLE_COMPILATION ON)
