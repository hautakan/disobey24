#include "pch.h"

#pragma comment(linker, "/export:CorGetSvc=mscorsvc2.CorGetSvc,@1")
#pragma comment(linker, "/export:DllMain=mscorsvc2.DllMain,@2")

BOOL APIENTRY DllMain(HMODULE hModule,
    DWORD  ul_reason_for_call,
    LPVOID lpReserved
)
{

    switch (ul_reason_for_call)
    {
    case DLL_PROCESS_ATTACH:
    {
        MessageBoxA(NULL, "Everything is broken, nothing is secure ;)", "Disobey 2024", 0);
    }
    case DLL_THREAD_ATTACH:
    case DLL_THREAD_DETACH:
    case DLL_PROCESS_DETACH:
        break;
    }
    return TRUE;
}
