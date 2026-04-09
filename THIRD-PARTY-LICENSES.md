# Third-Party Licenses

CapWarden bundles the following open-source software in the Windows installer.
Their inclusion does not imply endorsement by their respective authors.

## Direct Dependencies

### requests
- License: Apache-2.0
- Copyright: (c) Kenneth Reitz and contributors
- URL: https://github.com/psf/requests

### Pillow
- License: HPND (Historical Permission Notice and Disclaimer)
- Copyright: (c) 1997-2011 Secret Labs AB, (c) 1995-2011 Fredrik Lundh, (c) 2010-2026 Jeffrey A. Clark and contributors
- URL: https://github.com/python-pillow/Pillow

### pystray
- License: LGPL-3.0
- Copyright: (c) Moses Palmer
- URL: https://github.com/moses-palmer/pystray
- Note: Used as an unmodified library dependency. Users who wish to substitute
  a modified version of pystray can build CapWarden from source.

### pywebview
- License: BSD-3-Clause
- Copyright: (c) 2014-2017 Roman Sirokov
- URL: https://pywebview.flowrl.com

## Transitive Dependencies

### urllib3
- License: MIT
- Copyright: (c) 2008-2020 Andrey Petrov and contributors
- URL: https://github.com/urllib3/urllib3
- Required by: requests

### certifi
- License: MPL-2.0
- Copyright: (c) Kenneth Reitz
- URL: https://github.com/certifi/python-certifi
- Required by: requests
- Note: Mozilla CA certificate bundle. Distributed unmodified. Source available at the URL above.

### charset-normalizer
- License: MIT
- Copyright: (c) Ahmed R. TAHRI
- URL: https://github.com/jawah/charset_normalizer
- Required by: requests

### idna
- License: BSD-3-Clause
- Copyright: (c) 2013-2025 Kim Davies and contributors
- URL: https://github.com/kjd/idna
- Required by: requests

### pythonnet
- License: MIT
- Copyright: (c) The Contributors of the Python.NET Project
- URL: https://pythonnet.github.io/
- Required by: pywebview

### clr_loader
- License: MIT
- Copyright: (c) Benedikt Reinartz
- URL: https://github.com/pythonnet/clr-loader
- Required by: pythonnet

### cffi
- License: MIT
- Copyright: (c) Armin Rigo, Maciej Fijalkowski
- URL: https://github.com/python-cffi/cffi
- Required by: clr_loader

### pycparser
- License: BSD-3-Clause
- Copyright: (c) 2008-2022 Eli Bendersky
- URL: https://github.com/eliben/pycparser
- Required by: cffi

### bottle
- License: MIT
- Copyright: (c) Marcel Hellkamp
- URL: https://bottlepy.org/
- Required by: pywebview

### proxy_tools
- License: MIT
- Copyright: (c) Jonathan Tushman
- URL: https://github.com/jtushman/proxy_tools
- Required by: pywebview

### six
- License: MIT
- Copyright: (c) Benjamin Peterson
- URL: https://github.com/benjaminp/six
- Required by: pystray

### typing_extensions
- License: PSF-2.0
- Copyright: (c) Python Software Foundation
- URL: https://github.com/python/typing_extensions
- Required by: pywebview

## Runtime

### Python
- License: PSF-2.0
- Copyright: (c) 2001-2026 Python Software Foundation
- URL: https://docs.python.org/3/license.html

## License Texts

- Apache-2.0: https://www.apache.org/licenses/LICENSE-2.0
- BSD-3-Clause: https://opensource.org/licenses/BSD-3-Clause
- HPND: https://opensource.org/licenses/HPND
- LGPL-3.0: https://www.gnu.org/licenses/lgpl-3.0.html
- MIT: https://opensource.org/licenses/MIT
- MPL-2.0: https://www.mozilla.org/en-US/MPL/2.0/
- PSF-2.0: https://docs.python.org/3/license.html
