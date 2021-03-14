# android_aidl_dt_fix
android's aidl tool misbhave on some linux filesystems,this resolves one.


Google's quick/lazy code only works on a few modern FS,this adds fallbacks if source is placed on some old FS.
