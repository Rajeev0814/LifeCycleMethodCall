# LifeCycleMethodCall
Android Activity and Fragment lifecycle


when you add fragment in xml...................

function_fragment: onAttach
function_fragment: onCreate
function_fragment: onCreateView
function_fragment: onViewCreated
function_activity: onCreate
function_fragment: onActivityCreated
function_fragment: onStart
function_activity: onStart
function_activity: onResume
function_fragment: onResume
function_fragment: onPause
function_activity: onPause
function_fragment: onStop
function_activity: onStop
function_activity: onRestart
function_fragment: onStart
function_activity: onStart
function_activity: onResume
function_fragment: onResume


when you add fragment dynamically................

function_activity: onCreate
function_fragment: onAttach
function_fragment: onCreate
function_fragment: onCreateView
function_fragment: onViewCreated
function_fragment: onActivityCreated
function_fragment: onStart
function_activity: onStart
function_activity: onResume
function_fragment: onResume
function_fragment: onPause
function_activity: onPause
function_fragment: onStop
function_activity: onStop
function_activity: onRestart
function_fragment: onStart
function_activity: onStart
function_activity: onResume
function_fragment: onResume
