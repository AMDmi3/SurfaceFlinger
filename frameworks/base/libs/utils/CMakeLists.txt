add_library(utils
    Asset.cpp
    AssetDir.cpp
    AssetManager.cpp
    BufferedTextOutput.cpp
    CallStack.cpp
    Debug.cpp
    FileMap.cpp
    RefBase.cpp
    ResourceTypes.cpp
    SharedBuffer.cpp
    Static.cpp
    StopWatch.cpp
    String8.cpp
    String16.cpp
    SystemClock.cpp
    TextOutput.cpp
    Threads.cpp
    TimerProbe.cpp
    Timers.cpp
    VectorImpl.cpp
    ZipFileCRO.cpp
    ZipFileRO.cpp
    ZipUtils.cpp
    misc.cpp
    ported.cpp
    LogSocket.cpp
    Binder.cpp
    BpBinder.cpp
    IInterface.cpp
    IMemory.cpp
    IPCThreadState.cpp
    MemoryDealer.cpp
    MemoryBase.cpp
    MemoryHeapBase.cpp
    MemoryHeapPmem.cpp
    Parcel.cpp
    ProcessState.cpp
    IPermissionController.cpp
    IServiceManager.cpp
    Unicode.cpp
    BackupData.cpp
    BackupHelpers.cpp
    futex_synchro.c
    )

target_link_libraries(utils cutils z rt dl)

