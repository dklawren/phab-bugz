# This Source Code Form is subject to the terms of the Mozilla Public
# License, v. 2.0. If a copy of the MPL was not distributed with this
# file, You can obtain one at http://mozilla.org/MPL/2.0/.
#
# This Source Code Form is "Incompatible With Secondary Licenses", as
# defined by the Mozilla Public License, v. 2.0.

FROM mozilla/mozphab
MAINTAINER mars@mozilla.com

COPY wait-for-mysql.php /usr/local/bin/wait-for-mysql.php
RUN chmod +x /usr/local/bin/wait-for-mysql.php

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
