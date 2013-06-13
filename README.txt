THESE FILES ARE ALL OBSOLETE. Please migrate away from using the
".spec" files and the headers generated from them to the
XML Registry and headers generated from that. See
  http://www.opengl.org/registry/api/README.txt
for more information.

Files associated with the deprecated ".spec" OpenGL extension registry.

    gl.spec	    - GL function registry
    enum.spec	    - GL enumerant registry
    glx.spec	    - GLX function registry (incomplete - see glxext.spec)
    glxenum.spec    - GLX enumerant registry
    glu.spec	    - GLU function registry
    enumglu.spec    - GLU enumerant registry (should be renamed)
    wgl.spec	    - WGL function registry (incomplete, out of date)
    wglenum.spec    - WGL enumerant registry (based on master Microsoft registry)

Derivative files used to construct *ext.h extension interface headers
    and related development stuff.

THESE FILES MUST REMAIN SYNCHRONIZED WITH THE REGISTRY FILES ABOVE.

    enumext.spec    - GL enumerants in extension order
    glxenumext.spec - GLX enumerants in extension order
    wglenumext.spec - WGL enumerants in extension order

    glxext.spec     - GLX extension functions in extension order
    wglext.spec     - WGL extension functions in extension order

Other stuff:

    {gl,glx,wgl}.tm - Typemaps converting from specfile to C types
