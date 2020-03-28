# ie-window-open-null

Go to [test](https://hiraokahypertools.github.io/ie-window-open-null) page.

> Internet Explorer 7 on Windows Vista. Opening a new window from an application other than the Internet Explorer process may result in a NULL return value. This occurs because Internet Explorer runs in protected mode by default. Protected mode prevents applications from privileged access to Internet Explorer when that access spans process boundaries. Because this method opens windows in a new process, protected mode restricts access to the new window. For more information, please see Understanding and Working in Protected Mode Internet Explorer.

Try disabliing **Protected mode**. from [IHTMLWindow2 open](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/aa741489%28v%3dvs.85%29)
