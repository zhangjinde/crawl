## Copyright 2013 Mo McRoberts.
##
##  Licensed under the Apache License, Version 2.0 (the "License");
##  you may not use this file except in compliance with the License.
##  You may obtain a copy of the License at
##
##      http://www.apache.org/licenses/LICENSE-2.0
##
##  Unless required by applicable law or agreed to in writing, software
##  distributed under the License is distributed on an "AS IS" BASIS,
##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
##  See the License for the specific language governing permissions and
##  limitations under the License.
##

bin_PROGRAMS = crawl-fetch crawl-locate crawl-mirror crawl-config

crawl_fetch_LDADD = ../libcrawl.la
crawl_locate_LDADD = ../libcrawl.la
crawl_mirror_LDADD = ../libcrawl.la $(LIBXML2_LOCAL_LIBS) $(LIBXML2_LIBS)
