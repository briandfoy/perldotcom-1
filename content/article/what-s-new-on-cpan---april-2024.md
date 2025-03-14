{
   "title" : "What's new on CPAN - April 2024",
   "authors" : [
      "mathew-korica"
   ],
   "categories" : "cpan",
   "draft" : false,
   "thumbnail" : "/images/whats-new-on-cpan/black.svg",
   "date" : "2024-05-09T19:00:00",
   "image" : "/images/whats-new-on-cpan/black.svg",
   "description" : "A curated look at April's new CPAN uploads",
   "tags" : [
      "new"
   ]
}


Welcome to "What's new on CPAN", a curated look at last month's new CPAN uploads for your reading and programming pleasure. Enjoy!

APIs & Apps
-----------
* [App::papersway](https://metacpan.org/pod/App::papersway) (SPWHITTON) provides [PaperWM](https://github.com/paperwm/PaperWM)-like window management for [Sway](https://swaywm.org/) and [i3](https://i3wm.org/) window managers
* Sort lines of text from the command line using various reusable subroutine modules:
	* [Comparer](https://metacpan.org/pod/Comparer) with [App::sort_by_comparer](https://metacpan.org/pod/App::sort_by_comparer) (PERLANCAR)
	* [Sorter](https://metacpan.org/pod/Sorter) with [App::sort_by_sorter](https://metacpan.org/pod/App::sort_by_sorter) (PERLANCAR)
	* [SortKey](https://metacpan.org/pod/SortKey) with [App::sort_by_sortkey](https://metacpan.org/pod/App::sort_by_sortkey) (PERLANCAR)
* Access the [OpenExchangeRates](https://openexchangerates.org/) API with [Net::Async::OpenExchRates](https://metacpan.org/pod/Net::Async::OpenExchRates) (VNEALV)
* [AI::Ollama::Client](https://metacpan.org/pod/AI::Ollama::Client) (CORION) interfaces with [Ollama](https://github.com/ollama/ollama) language models


Config & Devops
---------------
* Find and build Microsoft's [ONNX Runtime](https://github.com/microsoft/onnxruntime) AI system with [Alien::onnxruntime](https://metacpan.org/pod/Alien::onnxruntime) (EGOR)
* [CPAN::Requirements::Dynamic](https://metacpan.org/pod/CPAN::Requirements::Dynamic) (LEONT) will check that your system meets the prerequisites specified by a CPAN distribution
* [Dist::Build](https://metacpan.org/pod/Dist::Build) (LEONT) provides another way to build and install Perl modules
* A couple of [Dist::Zilla](https://metacpan.org/pod/Dist::Zilla) plugins:
	* [Dist::Zilla::Plugin::DistBuild](https://metacpan.org/pod/Dist::Zilla::Plugin::DistBuild) (LEONT) for [CPAN::Requirements::Dynamic](https://metacpan.org/pod/CPAN::Requirements::Dynamic) (see above)
	* [Dist::Zilla::Plugin::DynamicPrereqs::Meta](https://metacpan.org/pod/Dist::Zilla::Plugin::DynamicPrereqs::Meta) (LEONT) for [Dist::Build](https://metacpan.org/pod/Dist::Build) (see above)


Data
----
* Load back [Data::Dumper](https://metacpan.org/pod/Data::Dumper) output via eval with [Data::Dumper::UnDumper](https://metacpan.org/pod/Data::Dumper::UnDumper) (BIGPRESH)
* Categorization of modules using modules with:
	* [Acme::CPANModules::BPOM::FoodRegistration](https://metacpan.org/pod/Acme::CPANModules::BPOM::FoodRegistration) (PERLANCAR) for modules pertaining to the Indonesian food and drug authority
	* [Acme::CPANModules::JSONVariants](https://metacpan.org/pod/Acme::CPANModules::JSONVariants) (PERLANCAR) for variants or extensions of JSON
* Use a [SortKey](https://metacpan.org/pod/SortKey) module with [Sort::Key](https://metacpan.org/pod/Sort::Key) via [Sort::Key::SortKey](https://metacpan.org/pod/Sort::Key::SortKey) (PERLANCAR)
* Get all the colors of the rainbow, sorted, from [SortExample::Color::Rainbow::EN](https://metacpan.org/pod/SortExample::Color::Rainbow::EN) (PERLANCAR)
* Generate [SortKey](https://metacpan.org/pod/SortKey)-based sort keys for:
	* the number of occurrences of a string or regex pattern using [SortKey::Num::pattern_count](https://metacpan.org/pod/SortKey::Num::pattern_count) (PERLANCAR)
	* the similarity to a reference string using [SortKey::Num::similarity](https://metacpan.org/pod/SortKey::Num::similarity) (PERLANCAR)
	* a date extracted from text using [SortKey::date_in_text](https://metacpan.org/pod/SortKey::date_in_text) (PERLANCAR)
* [SortSpec::Perl::CPAN::ChangesGroup::PERLANCAR](https://metacpan.org/pod/SortSpec::Perl::CPAN::ChangesGroup::PERLANCAR) provides a specification for sorting groups of text in CPAN change files (PERLANCAR)
* Sort by a [Comparer](https://metacpan.org/pod/Comparer) subroutine using [Sorter::from_comparer](https://metacpan.org/pod/Sorter::from_comparer) (PERLANCAR)
* Sort by keys generated by a [SortKey](https://metacpan.org/pod/SortKey) module with [Sorter::from_sortkey](https://metacpan.org/pod/Sorter::from_sortkey) (PERLANCAR)
* Generate short unique identifiers from numbers with [Sqids](https://metacpan.org/pod/Sqids) (MYSOCIETY)
* [TableData::Business::ID::BPOM::FoodAdditive](https://metacpan.org/pod/TableData::Business::ID::BPOM::FoodAdditive) (PERLANCAR) provides food additive data from the Indonesian food and drug authority
* A bevy of schemas employing the [Sah](https://metacpan.org/pod/Sah) schema format with:
	* [Sah::SchemaBundle::Business::ID::BCA](https://metacpan.org/pod/Sah::SchemaBundle::Business::ID::BCA) (PERLANCAR) for schemas related to BCA (Bank Central Asia) bank
	* [Sah::SchemaBundle::Business::ID::Mandiri](https://metacpan.org/pod/Sah::SchemaBundle::Business::ID::Mandiri) (PERLANCAR) for schemas related to Mandiri bank
	* [Sah::SchemaBundle::Comparer](https://metacpan.org/pod/Sah::SchemaBundle::Comparer) (PERLANCAR) for schemas related to [Comparer](https://metacpan.org/pod/Comparer)
	* [Sah::SchemaBundle::Perl](https://metacpan.org/pod/Sah::SchemaBundle::Perl) (PERLANCAR) for schemas related to Perl
	* [Sah::SchemaBundle::SortKey](https://metacpan.org/pod/Sah::SchemaBundle::SortKey) (PERLANCAR) for schemas related to [SortKey](https://metacpan.org/pod/SortKey)
	* [Sah::SchemaBundle::Sorter](https://metacpan.org/pod/Sah::SchemaBundle::Sorter) (PERLANCAR) for schemas related to [Sorter](https://metacpan.org/pod/Sorter)


Development & Version Control
-----------------------------
* Benchmark various ways to handle exceptions with [Bencher::Scenario::ExceptionHandling](https://metacpan.org/pod/Bencher::Scenario::ExceptionHandling) (PERLANCAR)
* [Data::MiniDumpX](https://metacpan.org/pod/Data::MiniDumpX) (PERLANCAR) supports [Plugin::System](https://metacpan.org/pod/Plugin::System)
* Generate fixtures for [DBD::Mock::Session](https://metacpan.org/pod/DBD::Mock::Session) with [DBD::Mock::Session::GenerateFixtures](https://metacpan.org/pod/DBD::Mock::Session::GenerateFixtures) (UXYZAB)
* [Net::EPP::Server](https://metacpan.org/pod/Net::EPP::Server) (GBROWN) provides a high-level framework for developing EPP (Extensible Provisioning Protocol) servers
* Load an [i3](https://i3wm.org/) workspace with [AnyEvent::I3X::Workspace::OnDemand](https://metacpan.org/pod/AnyEvent::I3X::Workspace::OnDemand) (WATERKIP)
* Parse and format datetimes from PDF's using [DateTime::Format::PDF](https://metacpan.org/pod/DateTime::Format::PDF) (SKIM)
* Stringify references in:
	* [Data::Dump::HTML::Collapsible](https://metacpan.org/pod/Data::Dump::HTML::Collapsible) with [Devel::Confess::Patch::UseDataDumpHTMLCollapsible](https://metacpan.org/pod/Devel::Confess::Patch::UseDataDumpHTMLCollapsible) (PERLANCAR)
	* [Data::Dump::HTML::PopUp](https://metacpan.org/pod/Data::Dump::HTML::PopUp) with [Devel::Confess::Patch::UseDataDumpHTMLPopUp](https://metacpan.org/pod/Devel::Confess::Patch::UseDataDumpHTMLPopUp) (PERLANCAR)
* [Test2::Tools::MIDI](https://metacpan.org/pod/Test2::Tools::MIDI) (JMATES) tests whether MIDI files contain particular MIDI structures and events
* [Carp::Object](https://metacpan.org/pod/Carp::Object) (DAMI) is an object-oriented replacement for [Carp](https://metacpan.org/pod/Carp) or [Carp::Clan](https://metacpan.org/pod/Carp::Clan)
* [Carp::Patch::OutputToBrowser](https://metacpan.org/pod/Carp::Patch::OutputToBrowser) (PERLANCAR) outputs a stacktrace to a web browser
* Easily profile code with [Tiny::Prof](https://metacpan.org/pod/Tiny::Prof) (TIMKA)
* [JSON::Ordered::Conditional](https://metacpan.org/pod/JSON::Ordered::Conditional) (LNATION) and [YAML::Ordered::Conditional](https://metacpan.org/pod/YAML::Ordered::Conditional) (LNATION) provide a conditional language for use within JSON and YAML, respectively
* Generate CSAF (Common Security Advisory Framework) documents with [CSAF](https://metacpan.org/pod/CSAF) (GDT)
* Generate DDL for database table creation using [CXC::DB::DDL](https://metacpan.org/pod/CXC::DB::DDL) (DJERIUS)
* [Comparer::date_in_text](https://metacpan.org/pod/Comparer::date_in_text) (PERLANCAR) is a [Comparer](https://metacpan.org/pod/Comparer) that uses dates extracted from text
* Validation routines for the [Mo](https://metacpan.org/pod/Mo) object system:
	* [Mo::utils::Country](https://metacpan.org/pod/Mo::utils::Country) (SKIM) for countries
	* [Mo::utils::TimeZone](https://metacpan.org/pod/Mo::utils::TimeZone) (SKIM) for timezones
* [Number::Iterator](https://metacpan.org/pod/Number::Iterator) (LNATION) is a simple iterator for numbers


Science & Mathematics
---------------------
* [Crypt::Passphrase::Bcrypt::Compat](https://metacpan.org/pod/Crypt::Passphrase::Bcrypt::Compat) (LEONT) provides a bcrypt encoder for [Crypt::Passphrase](https://metacpan.org/pod/Crypt::Passphrase)


Web
---
* In your [Catalyst](https://metacpan.org/pod/Catalyst) app, automatically put flash values into the next request's stash with [Catalyst::Plugin::Flash](https://metacpan.org/pod/Catalyst::Plugin::Flash) (ARISTOTLE)
* A whole slew of new plugins for the [Mojolicious](https://metacpan.org/pod/Mojolicious) framework:
	* Use [OpenID Connect](https://openid.net/developers/how-connect-works) authentication with [Mojolicious::Plugin::Authentication::OIDC](https://metacpan.org/pod/Mojolicious::Plugin::Authentication::OIDC) (TYRRMINAL)
	* Add more configuration options to [Mojolicious::Plugin::Cron](https://metacpan.org/pod/Mojolicious::Plugin::Cron) with [Mojolicious::Plugin::Cron::Scheduler](https://metacpan.org/pod/Mojolicious::Plugin::Cron::Scheduler) (TYRRMINAL)
	* Run Sqitch database migrations using [Mojolicious::Plugin::Migration::Sqitch](https://metacpan.org/pod/Mojolicious::Plugin::Migration::Sqitch) (TYRRMINAL)
	* Automatically load modules from namespaces with [Mojolicious::Plugin::Module::Loader](https://metacpan.org/pod/Mojolicious::Plugin::Module::Loader) (TYRRMINAL)
	* Access [DBIx::Class](https://metacpan.org/pod/DBIx::Class) with [Mojolicious::Plugin::ORM::DBIx](https://metacpan.org/pod/Mojolicious::Plugin::ORM::DBIx) (TYRRMINAL)
	* [Mojolicious::Plugin::SendEmail](https://metacpan.org/pod/Mojolicious::Plugin::SendEmail) for easily sending e-mails (TYRRMINAL)
	* Disable sessions with [Mojolicious::Plugin::Sessionless](https://metacpan.org/pod/Mojolicious::Plugin::Sessionless) (TYRRMINAL)
* [Plack::App::Login::Request](https://metacpan.org/pod/Plack::App::Login::Request) (SKIM) is a [Plack](https://metacpan.org/pod/Plack) application for requesting login information. [Tags::HTML::Login::Request](https://metacpan.org/pod/Tags::HTML::Login::Request) (SKIM) generates the supporting HTML and CSS
* Generate image-related HTML tags with [Tags::HTML::Image](https://metacpan.org/pod/Tags::HTML::Image) (SKIM)
* Use [Future](https://metacpan.org/pod/Future) on the web with [Web::Async](https://metacpan.org/pod/Web::Async) (TEAM)
* Render JSON-based data structures as HTML tables with [JSON::ToHTML](https://metacpan.org/pod/JSON::ToHTML) (ARISTOTLE)


Other
-----
* Perform basic arithmetic operations the paper and pencil way with [Arithmetic::PaperAndPencil](https://metacpan.org/pod/Arithmetic::PaperAndPencil) (JFORGET)




