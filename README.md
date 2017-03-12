UATHelper: Packaging (Windows (64-bit)): Running AutomationTool...
UATHelper: Packaging (Windows (64-bit)): Automation.ParseCommandLine: Parsing command line: -ScriptsForProject="C:/Users/Dont/Documents/Unreal Projects/RUN/RUN.uproject" BuildCookRun -nocompile -nocompileeditor -installed -nop4 -project="C:/Users/Dont/Documents/Unreal Projects/RUN/RUN.uproject" -cook -stage -archive -archivedirectory="C:/Users/Dont/Desktop/R
UN! - 64 Bit" -package -clientconfig=Development -ue4exe=UE4Editor-Cmd.exe -pak -prereqs -nodebuginfo -targetplatform=Win64 -build -CrashReporter -utf8output
UATHelper: Packaging (Windows (64-bit)): Automation.Process: Setting up command environment.
UATHelper: Packaging (Windows (64-bit)): BuildCookRun.SetupParams: Setting up ProjectParams for C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject
UATHelper: Packaging (Windows (64-bit)): Project.Build: ********** BUILD COMMAND STARTED **********
UATHelper: Packaging (Windows (64-bit)): CommandUtils.Run: Run: C:\Program Files\Epic Games\UE_4.15\Engine\Binaries\DotNET\UnrealBuildTool.exe RUN Win64 Development -Project="C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  "C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  -remoteini="C:\Users\Dont\Documents\Unreal Projects\RUN" -noxge -g
eneratemanifest -NoHotReload
UATHelper: Packaging (Windows (64-bit)): CommandUtils.Run: Run: Took 1.2740766s to run UnrealBuildTool.exe, ExitCode=0
UATHelper: Packaging (Windows (64-bit)): CommandUtils.Run: Run: C:\Program Files\Epic Games\UE_4.15\Engine\Binaries\DotNET\UnrealBuildTool.exe RUN Win64 Development -Project="C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  "C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  -remoteini="C:\Users\Dont\Documents\Unreal Projects\RUN" -noxge -N
oHotReload -ignorejunk
UATHelper: Packaging (Windows (64-bit)): UnrealBuildTool: Creating makefile for RUN (no existing makefile)
UATHelper: Packaging (Windows (64-bit)): UnrealBuildTool: Performing full C++ include scan (no include cache file)
UATHelper: Packaging (Windows (64-bit)): UnrealBuildTool: ERROR: Windows SDK v8.1 must be installed in order to build this target.
UATHelper: Packaging (Windows (64-bit)): CommandUtils.Run: Run: Took 4.2572542s to run UnrealBuildTool.exe, ExitCode=5
UATHelper: Packaging (Windows (64-bit)): Program.Main: ERROR: AutomationTool terminated with exception: AutomationTool.CommandUtils+CommandFailedException: Command failed (Result:5): C:\Program Files\Epic Games\UE_4.15\Engine\Binaries\DotNET\UnrealBuildTool.exe RUN Win64 Development -Project="C:\Users\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  "C:\Use
rs\Dont\Documents\Unreal Projects\RUN\RUN.uproject"  -remoteini="C:\Users\Dont\Documents\Unreal Projects\RUN" -noxge -NoHotReload -ignorejunk. See logfile for details: 'UnrealBuildTool-2017.03.11-21.38.44.txt' 
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.CommandUtils.RunAndLog(String App, String CommandLine, String Logfile, Int32 MaxSuccessCode, String Input, ERunOptions Options, Dictionary`2 EnvVars, SpewFilterCallbackType SpewFilterCallback)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.CommandUtils.RunAndLog(CommandEnvironment Env, String App, String CommandLine, String LogName, Int32 MaxSuccessCode, String Input, ERunOptions Options, Dictionary`2 EnvVars, SpewFilterCallbackType SpewFilterCallback)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.CommandUtils.RunUBT(CommandEnvironment Env, String UBTExecutable, String CommandLine, String LogName, Dictionary`2 EnvVars)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.CommandUtils.RunUBT(CommandEnvironment Env, String UBTExecutable, FileReference Project, String Target, String Platform, String Config, String AdditionalArgs, String LogName, Dictionary`2 EnvVars)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.UE4Build.BuildWithUBT(String TargetName, UnrealTargetPlatform TargetPlatform, String Config, FileReference UprojectPath, Boolean ForceMonolithic, Boolean ForceNonUnity, Boolean ForceDebugInfo, Boolean ForceFlushMac, Boolean DisableXGE, String InAddArgs, Boolean ForceUnity, Dictionary`2 EnvVars)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.UE4Build.Build(BuildAgenda Agenda, Nullable`1 InDeleteBuildProducts, Boolean InUpdateVersionFiles, Boolean InForceNoXGE, Boolean InUseParallelExecutor, Boolean InForceNonUnity, Boolean InForceUnity, Boolean InShowProgress, Dictionary`2 PlatformEnvVars, Nullable`1 InChangelistNumberOverride, Dictio
nary`2 InTargetToManifest)
UATHelper: Packaging (Windows (64-bit)):    at Project.Build(BuildCommand Command, ProjectParams Params, Int32 WorkingCL, ProjectBuildTargets TargetMask)
UATHelper: Packaging (Windows (64-bit)):    at BuildCookRun.DoBuildCookRun(ProjectParams Params)
UATHelper: Packaging (Windows (64-bit)):    at BuildCookRun.ExecuteBuild()
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.BuildCommand.Execute()
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.Automation.Execute(List`1 CommandsToExecute, CaselessDictionary`1 Commands)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.Automation.Process(String[] Arguments)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.Program.MainProc(Object Param)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.InternalUtils.RunSingleInstance(Func`2 Main, Object Param)
UATHelper: Packaging (Windows (64-bit)):    at AutomationTool.Program.Main()
UATHelper: Packaging (Windows (64-bit)): Program.Main: AutomationTool exiting with ExitCode=5 (5)
UATHelper: Packaging (Windows (64-bit)): BUILD FAILED
PackagingResults:Error: Error Unknown Error
