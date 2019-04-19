





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-OBabailf0Gja8rWVZO1xyYAw//CQdLOJF4riG050gTxsVqVD7az4Sq56hPWfv3AoaxuEhYXgQlGQcNxzZzDyVA==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-d69542a4a3958db914b3bec3f757de26.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-050KJxFEH07Kt5Aig+cjXwMQCq3+I/rz2ZB6Ob92EC2qPDzZDG3uA7EcSldvj/OQ97qS8ceo6AcKYwZXKJGOTA==" rel="stylesheet" href="https://github.githubassets.com/assets/site-309208b9537f52036f24dfe11dde6160.css" />
    <link crossorigin="anonymous" media="all" integrity="sha512-NuTIwC5UFn67DeQnzZUYtnS1vm5tRZ4BtBic9TpGK+RnuP+MH/OqIVS+Dr7rpnOwnSmxezyl1L50kLWW3sSNGQ==" rel="stylesheet" href="https://github.githubassets.com/assets/github-a7545a042547353ea45ba3211e585d1c.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>setup-ipsec-vpn/clients-zh.md at master · hwdsl2/setup-ipsec-vpn · GitHub</title>
    <meta name="description" content="Scripts to build your own IPsec VPN server, with IPsec/L2TP and Cisco IPsec on Ubuntu, Debian and CentOS - hwdsl2/setup-ipsec-vpn">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars3.githubusercontent.com/u/5104323?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="hwdsl2/setup-ipsec-vpn" /><meta name="twitter:description" content="Scripts to build your own IPsec VPN server, with IPsec/L2TP and Cisco IPsec on Ubuntu, Debian and CentOS - hwdsl2/setup-ipsec-vpn" />
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/5104323?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="hwdsl2/setup-ipsec-vpn" /><meta property="og:url" content="https://github.com/hwdsl2/setup-ipsec-vpn" /><meta property="og:description" content="Scripts to build your own IPsec VPN server, with IPsec/L2TP and Cisco IPsec on Ubuntu, Debian and CentOS - hwdsl2/setup-ipsec-vpn" />

  <link rel="assets" href="https://github.githubassets.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="C1C8:6C71:E82A5:1BA6B5:5CB93458" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="C1C8:6C71:E82A5:1BA6B5:5CB93458" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">


<meta class="js-ga-set" name="dimension1" content="Logged Out">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="Y2IwNGNhNmUyMWNiN2RlZDU1ODNiMjRiNzI3ODI4ZTQyZmY1ZjkwN2E0YjliZDQwN2I1OGVmOTQ3ZjhlNTNhNHx7InJlbW90ZV9hZGRyZXNzIjoiNzEuMzMuMTcwLjExMCIsInJlcXVlc3RfaWQiOiJDMUM4OjZDNzE6RTgyQTU6MUJBNkI1OjVDQjkzNDU4IiwidGltZXN0YW1wIjoxNTU1NjQxNDUyLCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_ENTERPRISE_CONTACTS,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS">

  <meta name="html-safe-nonce" content="96ef5d9c793099fb1f6e134e54e869c1d7441cae">

  <meta http-equiv="x-pjax-version" content="33f3b58b7c74071c0ca442c1f14c3b5d">
  

      <link href="https://github.com/hwdsl2/setup-ipsec-vpn/commits/master.atom" rel="alternate" title="Recent Commits to setup-ipsec-vpn:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/hwdsl2/setup-ipsec-vpn git https://github.com/hwdsl2/setup-ipsec-vpn.git">

  <meta name="octolytics-dimension-user_id" content="5104323" /><meta name="octolytics-dimension-user_login" content="hwdsl2" /><meta name="octolytics-dimension-repository_id" content="49217007" /><meta name="octolytics-dimension-repository_nwo" content="hwdsl2/setup-ipsec-vpn" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="49217007" /><meta name="octolytics-dimension-repository_network_root_nwo" content="hwdsl2/setup-ipsec-vpn" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">


  <meta name="u2f-enabled" content="true">


  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production emoji-size-boost page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


        <header class="Header-old header-logged-out  position-relative f4 py-2" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
        <a class="mr-4" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
          <svg height="32" class="octicon octicon-mark-github text-white" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
        </a>
    </div>

    <div class="HeaderMenu HeaderMenu--logged-out d-flex flex-justify-between flex-items-center flex-auto">
      <div class="d-none">
        <button class="btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
          <svg height="24" class="octicon octicon-x text-gray" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
        </button>
      </div>

        <nav class="mt-0" aria-label="Global">
          <ul class="d-flex list-style-none">
              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Why GitHub?
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>
                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 mt-0  p-4 left-n4 position-absolute">
                    <a href="/features" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Features">Features <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>
                    <ul class="list-style-none f5 pb-3">
                      <li class="edge-item-fix"><a href="/features/code-review/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code review">Code review</a></li>
                      <li class="edge-item-fix"><a href="/features/project-management/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Project management">Project management</a></li>
                      <li class="edge-item-fix"><a href="/features/integrations" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Integrations">Integrations</a></li>
                      <li class="edge-item-fix"><a href="/features/actions" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Actions">Actions</a>
                      <li class="edge-item-fix"><a href="/features#team-management" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Team management">Team management</a></li>
                      <li class="edge-item-fix"><a href="/features#social-coding" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Social coding">Social coding</a></li>
                      <li class="edge-item-fix"><a href="/features#documentation" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Documentation">Documentation</a></li>
                      <li class="edge-item-fix"><a href="/features#code-hosting" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code hosting">Code hosting</a></li>
                    </ul>

                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
                      <li class="edge-item-fix"><a href="/customer-stories" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Customer stories">Customer stories <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="/security" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Security">Security <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
              <li class=" mr-3 mr-lg-3">
                <a href="/enterprise" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Enterprise">Enterprise</a>
              </li>

              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Explore
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-0 mt-0  p-4 left-n4 position-absolute">
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/explore" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Explore">Explore GitHub <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2  border-top pt-3">Learn &amp; contribute</h4>
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/topics" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Topics">Topics</a></li>
                        <li class="edge-item-fix"><a href="/collections" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Collections">Collections</a></li>
                      <li class="edge-item-fix"><a href="/trending" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Trending">Trending</a></li>
                      <li class="edge-item-fix"><a href="https://lab.github.com/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Learning lab">Learning Lab</a></li>
                      <li class="edge-item-fix"><a href="https://opensource.guide" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Open source guides">Open source guides</a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2  border-top pt-3">Connect with others</h4>
                    <ul class="list-style-none mb-0">
                      <li class="edge-item-fix"><a href="https://github.com/events" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Events">Events</a></li>
                      <li class="edge-item-fix"><a href="https://github.community" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Community forum">Community forum</a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to GitHub Education">GitHub Education</a></li>
                    </ul>
                  </div>
                </details>
              </li>

              <li class=" mr-3 mr-lg-3">
                <a href="/marketplace" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Marketplace">Marketplace</a>
              </li>

              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Pricing
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                       <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-4 mt-0  p-4 left-n4 position-absolute">
                    <a href="/pricing" class="pb-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Pricing">Plans <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>

                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/pricing#feature-comparison" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Compare plans">Compare plans</a></li>
                      <li class="edge-item-fix"><a href="https://enterprise.github.com/contact" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Contact Sales">Contact Sales</a></li>
                    </ul>

                    <ul class="list-style-none mb-0  border-top pt-3">
                      <li class="edge-item-fix"><a href="/nonprofit" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Nonprofits">Nonprofit <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover"  data-ga-click="(Logged out) Header, go to Education">Education <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
          </ul>
        </nav>

      <div class="d-flex flex-items-center px-0 text-center text-left">
          <div class="d-lg-flex ">
            <div class="header-search mr-3 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="49217007" data-scoped-search-url="/hwdsl2/setup-ipsec-vpn/search" data-unscoped-search-url="/search" action="/hwdsl2/setup-ipsec-vpn/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search"
          data-unscoped-placeholder="Search GitHub"
          data-scoped-placeholder="Search"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=AvxhhkD1IAAlZmUq7fwxRIDOzMpmv77LluBsMniZxYum8svCvRVx1DFL69FOc/kF/1IIS63hSwAS8nJemQiOJA=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


</ul>

            </div>
      </label>
</form>  </div>
</div>

          </div>

        <a class="HeaderMenu-link no-underline mr-3" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="d0a3851b5060be085f2cd61969aa44a46f062e920afd0d42884c176961177a6c" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in" href="/login?return_to=%2Fhwdsl2%2Fsetup-ipsec-vpn%2Fblob%2Fmaster%2Fdocs%2Fclients-zh.md">
          Sign&nbsp;in
</a>          <a class="HeaderMenu-link d-inline-block no-underline border border-gray-dark rounded-1 px-2 py-1" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="2abf9e9b737440d230268f34e4076581f2ce93702f01ee73a79d80060c6c1c0a" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up" href="/join">
            Sign&nbsp;up
</a>      </div>
    </div>
  </div>
</header>

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main id="js-repo-pjax-container" data-pjax-container >
      


  






  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">



  <li>
    
  <a class="tooltipped tooltipped-s btn btn-sm btn-with-count" aria-label="You must be signed in to watch a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;notification subscription menu watch&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="a5a736d91b21a76cc18cfb528ac1f64f32b5173e14a362f4c56002f4ae82a5eb" href="/login?return_to=%2Fhwdsl2%2Fsetup-ipsec-vpn">
    <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
</a>    <a class="social-count" href="/hwdsl2/setup-ipsec-vpn/watchers"
       aria-label="466 users are watching this repository">
      466
    </a>

  </li>

  <li>
        <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to star a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;star button&quot;,&quot;repository_id&quot;:49217007,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="46c3d2bd216005687add7397ec4c8e6dc255bc3d34047d853613ebd4cc4f8b21" href="/login?return_to=%2Fhwdsl2%2Fsetup-ipsec-vpn">
      <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
      Star
</a>
    <a class="social-count js-social-count" href="/hwdsl2/setup-ipsec-vpn/stargazers"
      aria-label="9360 users starred this repository">
      9,360
    </a>

  </li>

  <li>
      <a class="btn btn-sm btn-with-count tooltipped tooltipped-s" aria-label="You must be signed in to fork a repository" rel="nofollow" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;repo details fork button&quot;,&quot;repository_id&quot;:49217007,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="016a52695e6dd368196a5f780f64209d6690199d17f9ecf7a04c81446a6f681a" href="/login?return_to=%2Fhwdsl2%2Fsetup-ipsec-vpn">
        <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
</a>
    <a href="/hwdsl2/setup-ipsec-vpn/network/members" class="social-count"
       aria-label="2391 users forked this repository">
      2,391
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=5104323" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/hwdsl2">hwdsl2</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/hwdsl2/setup-ipsec-vpn">setup-ipsec-vpn</a></strong>
  

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /hwdsl2/setup-ipsec-vpn" href="/hwdsl2/setup-ipsec-vpn">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /hwdsl2/setup-ipsec-vpn/issues" href="/hwdsl2/setup-ipsec-vpn/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /hwdsl2/setup-ipsec-vpn/pulls" href="/hwdsl2/setup-ipsec-vpn/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>






    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people alerts /hwdsl2/setup-ipsec-vpn/pulse" href="/hwdsl2/setup-ipsec-vpn/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>


  </div>
<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
    



  
    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/hwdsl2/setup-ipsec-vpn/blob/e61efe242e6ec9693603b91f1016bdb9a34fb9f2/docs/clients-zh.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:632360928e9e23dd546be3da1b6cde88 -->

        <div class="signup-prompt-bg rounded-1">
      <div class="signup-prompt p-4 text-center mb-4 rounded-1">
        <div class="position-relative">
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/site/dismiss_signup_prompt" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="O/QJXv/3uGEAIUPK9FLJeUYH0npBMrU1wwGfk6QH7U7jN8VqowAvAV8kRoVdovU+KHwGzDQEJCXRKu+LCOESYQ==" />
            <button type="submit" class="position-absolute top-0 right-0 btn-link link-gray" data-ga-click="(Logged out) Sign up prompt, clicked Dismiss, text:dismiss">
              Dismiss
            </button>
</form>          <h3 class="pt-2">Join GitHub today</h3>
          <p class="col-6 mx-auto">GitHub is home to over 31 million developers working together to host and review code, manage projects, and build software together.</p>
          <a class="btn btn-primary" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;files signup prompt&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;client_id&quot;:&quot;953960511.1555623754&quot;,&quot;originating_request_id&quot;:&quot;C1C8:6C71:E82A5:1BA6B5:5CB93458&quot;,&quot;originating_url&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md&quot;,&quot;referrer&quot;:&quot;https://github.com/hwdsl2/setup-ipsec-vpn/tree/master/docs&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="0fbd10a60b0ce177991dad566b156b245c931be21757df79608069bde9af5bac" data-ga-click="(Logged out) Sign up prompt, clicked Sign up, text:sign-up" href="/join?source=prompt-blob-show">Sign up</a>
        </div>
      </div>
    </div>


    <div class="d-flex flex-items-start mb-3">
      <span class="d-flex flex-justify-between">
        
<details class="details-reset details-overlay select-menu branch-select-menu ">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target">master</span>
  </summary>

  <details-menu class="select-menu-modal position-absolute" style="z-index: 99;" src="/hwdsl2/setup-ipsec-vpn/ref-list/master/docs/clients-zh.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-none">
          <a href="/hwdsl2/setup-ipsec-vpn/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="docs/clients-zh.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal ml-2 mr-3">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/hwdsl2/setup-ipsec-vpn"><span>setup-ipsec-vpn</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/hwdsl2/setup-ipsec-vpn/tree/master/docs"><span>docs</span></a></span><span class="separator">/</span><strong class="final-path">clients-zh.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-inline-block">
        <a href="/hwdsl2/setup-ipsec-vpn/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="docs/clients-zh.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    
  <div class="Box Box--condensed d-flex flex-column flex-shrink-0">
      <div class="Box-body d-flex flex-justify-between bg-blue-light flex-column flex-md-row flex-items-start flex-md-items-center">
        <span class="pr-md-4 f6">
          <a rel="author" data-skip-pjax="true" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=5104323" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/hwdsl2"><img class="avatar" src="https://avatars2.githubusercontent.com/u/5104323?s=40&amp;v=4" width="20" height="20" alt="@hwdsl2" /></a>
          <a class="text-bold link-gray-dark lh-default v-align-middle" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=5104323" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/hwdsl2">hwdsl2</a>
            <span class="lh-default v-align-middle">
              <a data-pjax="true" title="Update docs" class="link-gray" href="/hwdsl2/setup-ipsec-vpn/commit/0679c66071755d804aea68ea7474550c8942b2e7">Update docs</a>
            </span>
        </span>
        <span class="d-inline-block flex-shrink-0 v-align-bottom f6 mt-2 mt-md-0">
          <a class="pr-2 text-mono link-gray" href="/hwdsl2/setup-ipsec-vpn/commit/0679c66071755d804aea68ea7474550c8942b2e7" data-pjax>0679c66</a>
          <relative-time datetime="2019-02-09T22:24:19Z">Feb 9, 2019</relative-time>
        </span>
      </div>

    <div class="Box-body d-flex flex-items-center flex-auto f6 border-bottom-0 flex-wrap" >
      <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
        <summary class="btn-link" aria-haspopup="dialog">
          <span><strong>2</strong> contributors</span>
        </summary>
        <details-dialog
          class="Box Box--overlay d-flex flex-column anim-fade-in fast"
          aria-label="Users who have contributed to this file"
          >
          <div class="Box-header">
            <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
              <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
            </button>
            <h3 class="Box-title">
              Users who have contributed to this file
            </h3>
          </div>
              <ul class="list-style-none overflow-auto">
    <li class="Box-row">
      <a class="link-gray-dark no-underline" href="/hwdsl2">
        <img class="avatar mr-1" alt="" src="https://avatars2.githubusercontent.com/u/5104323?s=40&amp;v=4" width="20" height="20" />
        hwdsl2
</a>    </li>
    <li class="Box-row">
      <a class="link-gray-dark no-underline" href="/anydream">
        <img class="avatar mr-1" alt="" src="https://avatars3.githubusercontent.com/u/3724537?s=40&amp;v=4" width="20" height="20" />
        anydream
</a>    </li>
</ul>

        </details-dialog>
      </details>
        <span class="d-none d-md-inline-block">
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=5104323" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/hwdsl2/setup-ipsec-vpn/commits/master/docs/clients-zh.md?author=hwdsl2">
      <img class="avatar mr-1" src="https://avatars2.githubusercontent.com/u/5104323?s=40&amp;v=4" width="20" height="20" alt="@hwdsl2" /> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=3724537" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/hwdsl2/setup-ipsec-vpn/commits/master/docs/clients-zh.md?author=anydream">
      <img class="avatar mr-1" src="https://avatars3.githubusercontent.com/u/3724537?s=40&amp;v=4" width="20" height="20" alt="@anydream" /> 
</a>
</span>

    </div>
  </div>





    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-justify-between flex-items-center">

  <div class="text-mono f6">
      549 lines (398 sloc)
      <span class="file-info-divider"></span>
    23.8 KB
  </div>

  <div class="d-flex">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/hwdsl2/setup-ipsec-vpn/raw/master/docs/clients-zh.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/hwdsl2/setup-ipsec-vpn/blame/master/docs/clients-zh.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/hwdsl2/setup-ipsec-vpn/commits/master/docs/clients-zh.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:mac">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

          <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
            aria-label="You must be signed in to make or propose changes">
            <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
          </button>
          <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
            aria-label="You must be signed in to make or propose changes">
            <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
          </button>
    </div>
  </div>
</div>

      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-5" itemprop="text"><h1><a id="user-content-配置-ipsecl2tp-vpn-客户端" class="anchor" aria-hidden="true" href="#配置-ipsecl2tp-vpn-客户端"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>配置 IPsec/L2TP VPN 客户端</h1>
<p><em>其他语言版本: <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients.md">English</a>, <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md">简体中文</a>.</em></p>
<p><strong>注： 你也可以使用更高效的 <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-xauth-zh.md">IPsec/XAuth 模式</a> 连接，或者配置 <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/ikev2-howto-zh.md">IKEv2</a>。</strong></p>
<p>在成功 <a href="/hwdsl2/setup-ipsec-vpn/blob/master/README-zh.md">搭建自己的 VPN 服务器</a> 之后，按照下面的步骤来配置你的设备。IPsec/L2TP 在 Android, iOS, OS X 和 Windows 上均受支持，无需安装额外的软件。设置过程通常只需要几分钟。如果无法连接,请首先检查是否输入了正确的 VPN 登录凭证。</p>
<hr>
<ul>
<li>平台名称
<ul>
<li><a href="#windows">Windows</a></li>
<li><a href="#os-x">OS X (macOS)</a></li>
<li><a href="#android">Android</a></li>
<li><a href="#ios">iOS (iPhone/iPad)</a></li>
<li><a href="#chromebook">Chromebook</a></li>
<li><a href="#linux">Linux</a></li>
</ul>
</li>
<li><a href="#%E6%95%85%E9%9A%9C%E6%8E%92%E9%99%A4">故障排除</a></li>
</ul>
<h2><a id="user-content-windows" class="anchor" aria-hidden="true" href="#windows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows</h2>
<h3><a id="user-content-windows-10-and-8x" class="anchor" aria-hidden="true" href="#windows-10-and-8x"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 10 and 8.x</h3>
<ol>
<li>右键单击系统托盘中的无线/网络图标。</li>
<li>选择 <strong>打开网络和共享中心</strong>。或者，如果你使用 Windows 10 版本 1709 或以上，选择 <strong>打开"网络和 Internet"设置</strong>，然后在打开的页面中单击 <strong>网络和共享中心</strong>。</li>
<li>单击 <strong>设置新的连接或网络</strong>。</li>
<li>选择 <strong>连接到工作区</strong>，然后单击 <strong>下一步</strong>。</li>
<li>单击 <strong>使用我的Internet连接 (VPN)</strong>。</li>
<li>在 <strong>Internet地址</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>目标名称</strong> 字段中输入任意内容。单击 <strong>创建</strong>。</li>
<li>返回 <strong>网络和共享中心</strong>。单击左侧的 <strong>更改适配器设置</strong>。</li>
<li>右键单击新创建的 VPN 连接，并选择 <strong>属性</strong>。</li>
<li>单击 <strong>安全</strong> 选项卡，从 <strong>VPN 类型</strong> 下拉菜单中选择 "使用 IPsec 的第 2 层隧道协议 (L2TP/IPSec)"。</li>
<li>单击 <strong>允许使用这些协议</strong>。选中 "质询握手身份验证协议 (CHAP)" 和 "Microsoft CHAP 版本 2 (MS-CHAP v2)" 复选框。</li>
<li>单击 <strong>高级设置</strong> 按钮。</li>
<li>单击 <strong>使用预共享密钥作身份验证</strong> 并在 <strong>密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>单击 <strong>确定</strong> 关闭 <strong>高级设置</strong>。</li>
<li>单击 <strong>确定</strong> 保存 VPN 连接的详细信息。</li>
</ol>
<p><strong>注：</strong> 在首次连接之前需要<strong>修改一次注册表</strong>。请参见下面的说明。</p>
<p>另外，除了按照以上步骤操作，你也可以运行下面的 Windows PowerShell 命令来创建 VPN 连接。将 <code>你的 VPN 服务器 IP</code> 和 <code>你的 VPN IPsec PSK</code> 换成你自己的值，用单引号括起来：</p>
<div class="highlight highlight-text-shell-session"><pre># <span class="pl-s1">不保存命令行历史记录</span>
<span class="pl-c1">Set-PSReadlineOption –HistorySaveStyle SaveNothing</span>
# <span class="pl-s1">创建 VPN 连接</span>
<span class="pl-c1">Add-VpnConnection -Name 'My IPsec VPN' -ServerAddress '你的 VPN 服务器 IP' -L2tpPsk '你的 VPN IPsec PSK' -TunnelType L2tp -EncryptionLevel Required -AuthenticationMethod Chap,MSChapv2 -Force -RememberCredential -PassThru</span>
# <span class="pl-s1">忽略 data encryption 警告（数据在 IPsec 隧道中已被加密）</span></pre></div>
<h3><a id="user-content-windows-7-vista-and-xp" class="anchor" aria-hidden="true" href="#windows-7-vista-and-xp"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 7, Vista and XP</h3>
<ol>
<li>单击开始菜单，选择控制面板。</li>
<li>进入 <strong>网络和Internet</strong> 部分。</li>
<li>单击 <strong>网络和共享中心</strong>。</li>
<li>单击 <strong>设置新的连接或网络</strong>。</li>
<li>选择 <strong>连接到工作区</strong>，然后单击 <strong>下一步</strong>。</li>
<li>单击 <strong>使用我的Internet连接 (VPN)</strong>。</li>
<li>在 <strong>Internet地址</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>目标名称</strong> 字段中输入任意内容。</li>
<li>选中 <strong>现在不连接；仅进行设置以便稍后连接</strong> 复选框。</li>
<li>单击 <strong>下一步</strong>。</li>
<li>在 <strong>用户名</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>在 <strong>密码</strong> 字段中输入<code>你的 VPN 密码</code>。</li>
<li>选中 <strong>记住此密码</strong> 复选框。</li>
<li>单击 <strong>创建</strong>，然后单击 <strong>关闭</strong> 按钮。</li>
<li>返回 <strong>网络和共享中心</strong>。单击左侧的 <strong>更改适配器设置</strong>。</li>
<li>右键单击新创建的 VPN 连接，并选择 <strong>属性</strong>。</li>
<li>单击 <strong>选项</strong> 选项卡，取消选中 <strong>包括Windows登录域</strong> 复选框。</li>
<li>单击 <strong>安全</strong> 选项卡，从 <strong>VPN 类型</strong> 下拉菜单中选择 "使用 IPsec 的第 2 层隧道协议 (L2TP/IPSec)"。</li>
<li>单击 <strong>允许使用这些协议</strong>。选中 "质询握手身份验证协议 (CHAP)" 和 "Microsoft CHAP 版本 2 (MS-CHAP v2)" 复选框。</li>
<li>单击 <strong>高级设置</strong> 按钮。</li>
<li>单击 <strong>使用预共享密钥作身份验证</strong> 并在 <strong>密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>单击 <strong>确定</strong> 关闭 <strong>高级设置</strong>。</li>
<li>单击 <strong>确定</strong> 保存 VPN 连接的详细信息。</li>
</ol>
<p><strong>注：</strong> 在首次连接之前需要<a href="#windows-错误-809">修改一次注册表</a>，以解决 VPN 服务器 和/或 客户端与 NAT （比如家用路由器）的兼容问题。</p>
<p>要连接到 VPN： 单击系统托盘中的无线/网络图标，选择新的 VPN 连接，然后单击 <strong>连接</strong>。如果出现提示，在登录窗口中输入 <code>你的 VPN 用户名</code> 和 <code>密码</code> ，并单击 <strong>确定</strong>。最后你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<p>如果在连接过程中遇到错误，请参见 <a href="#故障排除">故障排除</a>。</p>
<h2><a id="user-content-os-x" class="anchor" aria-hidden="true" href="#os-x"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>OS X</h2>
<ol>
<li>打开系统偏好设置并转到网络部分。</li>
<li>在窗口左下角单击 <strong>+</strong> 按钮。</li>
<li>从 <strong>接口</strong> 下拉菜单选择 <strong>VPN</strong>。</li>
<li>从 <strong>VPN类型</strong> 下拉菜单选择 <strong>IPSec 上的 L2TP</strong>。</li>
<li>在 <strong>服务名称</strong> 字段中输入任意内容。</li>
<li>单击 <strong>创建</strong>。</li>
<li>在 <strong>服务器地址</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>帐户名称</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>单击 <strong>鉴定设置</strong> 按钮。</li>
<li>在 <strong>用户鉴定</strong> 部分，选择 <strong>密码</strong> 单选按钮，然后输入<code>你的 VPN 密码</code>。</li>
<li>在 <strong>机器鉴定</strong> 部分，选择 <strong>共享的密钥</strong> 单选按钮，然后输入<code>你的 VPN IPsec PSK</code>。</li>
<li>单击 <strong>好</strong>。</li>
<li>选中 <strong>在菜单栏中显示 VPN 状态</strong> 复选框。</li>
<li><strong>（重要）</strong> 单击 <strong>高级</strong> 按钮，并选中 <strong>通过VPN连接发送所有通信</strong> 复选框。</li>
<li>单击 <strong>TCP/IP</strong> 选项卡，并在 <strong>配置IPv6</strong> 部分中选择 <strong>仅本地链接</strong>。</li>
<li>单击 <strong>好</strong> 关闭高级设置，然后单击 <strong>应用</strong> 保存VPN连接信息。</li>
</ol>
<p>要连接到 VPN： 使用菜单栏中的图标，或者打开系统偏好设置的网络部分，选择 VPN 并单击 <strong>连接</strong>。最后你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<p>如果在连接过程中遇到错误，请参见 <a href="#故障排除">故障排除</a>。</p>
<h2><a id="user-content-android" class="anchor" aria-hidden="true" href="#android"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Android</h2>
<ol>
<li>启动 <strong>设置</strong> 应用程序。</li>
<li>在 <strong>无线和网络</strong> 部分单击 <strong>更多...</strong>。</li>
<li>单击 <strong>VPN</strong>。</li>
<li>单击 <strong>添加VPN配置文件</strong> 或窗口右上角的 <strong>+</strong>。</li>
<li>在 <strong>名称</strong> 字段中输入任意内容。</li>
<li>在 <strong>类型</strong> 下拉菜单选择 <strong>L2TP/IPSec PSK</strong>。</li>
<li>在 <strong>服务器地址</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>IPSec 预共享密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>单击 <strong>保存</strong>。</li>
<li>单击新的VPN连接。</li>
<li>在 <strong>用户名</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>在 <strong>密码</strong> 字段中输入<code>你的 VPN 密码</code>。</li>
<li>选中 <strong>保存帐户信息</strong> 复选框。</li>
<li>单击 <strong>连接</strong>。</li>
</ol>
<p>VPN 连接成功后，会在通知栏显示图标。最后你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<p>如果在连接过程中遇到错误，请参见 <a href="#故障排除">故障排除</a>。</p>
<h2><a id="user-content-ios" class="anchor" aria-hidden="true" href="#ios"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>iOS</h2>
<ol>
<li>进入设置 -&gt; 通用 -&gt; VPN。</li>
<li>单击 <strong>添加VPN配置...</strong>。</li>
<li>单击 <strong>类型</strong> 。选择 <strong>L2TP</strong> 并返回。</li>
<li>在 <strong>描述</strong> 字段中输入任意内容。</li>
<li>在 <strong>服务器</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>帐户</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>在 <strong>密码</strong> 字段中输入<code>你的 VPN 密码</code>。</li>
<li>在 <strong>密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>启用 <strong>发送所有流量</strong> 选项。</li>
<li>单击右上角的 <strong>完成</strong>。</li>
<li>启用 <strong>VPN</strong> 连接。</li>
</ol>
<p>VPN 连接成功后，会在通知栏显示图标。最后你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<p>如果在连接过程中遇到错误，请参见 <a href="#故障排除">故障排除</a>。</p>
<h2><a id="user-content-chromebook" class="anchor" aria-hidden="true" href="#chromebook"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Chromebook</h2>
<ol>
<li>如果你尚未登录 Chromebook，请先登录。</li>
<li>单击状态区（其中显示你的帐户头像）。</li>
<li>单击 <strong>设置</strong>。</li>
<li>在 <strong>互联网连接</strong> 部分，单击 <strong>添加连接</strong>。</li>
<li>单击 <strong>添加 OpenVPN / L2TP</strong>。</li>
<li>在 <strong>服务器主机名</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>服务名称</strong> 字段中输入任意内容。</li>
<li>在 <strong>供应商类型</strong> 下拉菜单选择 <strong>L2TP/IPsec + 预共享密钥</strong>。</li>
<li>在 <strong>预共享密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>在 <strong>用户名</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>在 <strong>密码</strong> 字段中输入<code>你的 VPN 密码</code>。</li>
<li>单击 <strong>连接</strong>。</li>
</ol>
<p>VPN 连接成功后，网络状态图标上会出现 VPN 指示。最后你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<p>如果在连接过程中遇到错误，请参见 <a href="#故障排除">故障排除</a>。</p>
<h2><a id="user-content-linux" class="anchor" aria-hidden="true" href="#linux"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Linux</h2>
<h3><a id="user-content-ubuntu-linux" class="anchor" aria-hidden="true" href="#ubuntu-linux"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Ubuntu Linux</h3>
<p>Ubuntu 18.04 （和更新版本）用户可以安装 <a href="https://packages.ubuntu.com/search?keywords=network-manager-l2tp-gnome" rel="nofollow">network-manager-l2tp-gnome</a> 软件包，然后通过 GUI 配置 IPsec/L2TP VPN 客户端。Ubuntu 16.04 和 14.04 用户可能需要添加 <code>nm-l2tp</code> PPA，参见 <a href="https://medium.com/@hkdb/ubuntu-16-04-connecting-to-l2tp-over-ipsec-via-network-manager-204b5d475721" rel="nofollow">这里</a>。</p>
<ol>
<li>进入 Settings -&gt; Network -&gt; VPN。单击 <strong>+</strong> 按钮。</li>
<li>选择 <strong>Layer 2 Tunneling Protocol (L2TP)</strong>。</li>
<li>在 <strong>Name</strong> 字段中输入任意内容。</li>
<li>在 <strong>Gateway</strong> 字段中输入<code>你的 VPN 服务器 IP</code>。</li>
<li>在 <strong>User name</strong> 字段中输入<code>你的 VPN 用户名</code>。</li>
<li>右键单击 <strong>Password</strong> 字段中的 <strong>?</strong>，选择 <strong>Store the password only for this user</strong>。</li>
<li>在 <strong>Password</strong> 字段中输入<code>你的 VPN 密码</code>。</li>
<li>保持 <strong>NT Domain</strong> 字段空白。</li>
<li>单击 <strong>IPsec Settings...</strong> 按钮。</li>
<li>选中 <strong>Enable IPsec tunnel to L2TP host</strong> 复选框。</li>
<li>保持 <strong>Gateway ID</strong> 字段空白。</li>
<li>在 <strong>Pre-shared key</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>展开 <strong>Advanced</strong> 部分。</li>
<li>在 <strong>Phase1 Algorithms</strong> 字段中输入 <code>aes128-sha1-modp2048!</code>。</li>
<li>在 <strong>Phase2 Algorithms</strong> 字段中输入 <code>aes128-sha1-modp2048!</code>。</li>
<li>单击 <strong>OK</strong>，然后单击 <strong>Add</strong> 保存 VPN 连接信息。</li>
<li>启用 <strong>VPN</strong> 连接。</li>
</ol>
<p>VPN 连接成功后，你可以到 <a href="https://www.ipchicken.com" rel="nofollow">这里</a> 检测你的 IP 地址，应该显示为<code>你的 VPN 服务器 IP</code>。</p>
<h3><a id="user-content-fedora-和-centos" class="anchor" aria-hidden="true" href="#fedora-和-centos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Fedora 和 CentOS</h3>
<p>Fedora 28 （和更新版本）和 CentOS 7 用户可以使用更高效的 <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-xauth-zh.md#linux">IPsec/XAuth</a> 模式连接。</p>
<h3><a id="user-content-其它-linux" class="anchor" aria-hidden="true" href="#其它-linux"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>其它 Linux</h3>
<p>首先看 <a href="https://github.com/nm-l2tp/network-manager-l2tp/wiki/Prebuilt-Packages">这里</a> 以确认 <code>network-manager-l2tp</code> 和 <code>network-manager-l2tp-gnome</code> 软件包是否在你的 Linux 版本上可用。如果可用，安装它们（选择使用 strongSwan）并参见上面的说明。另外，你也可以 <a href="#%E4%BD%BF%E7%94%A8%E5%91%BD%E4%BB%A4%E8%A1%8C%E9%85%8D%E7%BD%AE-linux-vpn-%E5%AE%A2%E6%88%B7%E7%AB%AF">使用命令行配置 Linux VPN 客户端</a>。</p>
<h2><a id="user-content-故障排除" class="anchor" aria-hidden="true" href="#故障排除"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>故障排除</h2>
<p><em>其他语言版本: <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients.md#troubleshooting">English</a>, <a href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md#%E6%95%85%E9%9A%9C%E6%8E%92%E9%99%A4">简体中文</a>.</em></p>
<ul>
<li><a href="#windows-%E9%94%99%E8%AF%AF-809">Windows 错误 809</a></li>
<li><a href="#windows-%E9%94%99%E8%AF%AF-628">Windows 错误 628</a></li>
<li><a href="#windows-10-%E5%8D%87%E7%BA%A7">Windows 10 升级</a></li>
<li><a href="#windows-810-dns-%E6%B3%84%E6%BC%8F">Windows 8/10 DNS 泄漏</a></li>
<li><a href="#macos-vpn-%E6%B5%81%E9%87%8F">macOS VPN 流量</a></li>
<li><a href="#iosandroid-%E7%9D%A1%E7%9C%A0%E6%A8%A1%E5%BC%8F">iOS/Android 睡眠模式</a></li>
<li><a href="#android-6-%E5%8F%8A%E4%BB%A5%E4%B8%8A%E7%89%88%E6%9C%AC">Android 6 及以上版本</a></li>
<li><a href="#chromebook-%E8%BF%9E%E6%8E%A5%E9%97%AE%E9%A2%98">Chromebook 连接问题</a></li>
<li><a href="#%E5%85%B6%E5%AE%83%E9%94%99%E8%AF%AF">其它错误</a></li>
<li><a href="#%E9%A2%9D%E5%A4%96%E7%9A%84%E6%AD%A5%E9%AA%A4">额外的步骤</a></li>
</ul>
<h3><a id="user-content-windows-错误-809" class="anchor" aria-hidden="true" href="#windows-错误-809"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 错误 809</h3>
<blockquote>
<p>无法建立计算机与 VPN 服务器之间的网络连接，因为远程服务器未响应。</p>
</blockquote>
<p>要解决此错误，在首次连接之前需要<a href="https://documentation.meraki.com/MX-Z/Client_VPN/Troubleshooting_Client_VPN#Windows_Error_809" rel="nofollow">修改一次注册表</a>，以解决 VPN 服务器 和/或 客户端与 NAT （比如家用路由器）的兼容问题。请下载并导入下面的 <code>.reg</code> 文件，或者打开 <a href="http://www.cnblogs.com/xxcanghai/p/4610054.html" rel="nofollow">提升权限命令提示符</a> 并运行以下命令。<strong>完成后必须重启计算机。</strong></p>
<ul>
<li>
<p>适用于 Windows Vista, 7, 8.x 和 10 (<a href="https://static.ls20.com/reg-files/v1/Fix_VPN_Error_809_Windows_Vista_7_8_10_Reboot_Required.reg" rel="nofollow">下载 .reg 文件</a>)</p>
<div class="highlight highlight-text-shell-session"><pre><span class="pl-c1">REG ADD HKLM\SYSTEM\CurrentControlSet\Services\PolicyAgent /v AssumeUDPEncapsulationContextOnSendRule /t REG_DWORD /d 0x2 /f</span></pre></div>
</li>
<li>
<p>仅适用于 Windows XP (<a href="https://static.ls20.com/reg-files/v1/Fix_VPN_Error_809_Windows_XP_ONLY_Reboot_Required.reg" rel="nofollow">下载 .reg 文件</a>)</p>
<div class="highlight highlight-text-shell-session"><pre><span class="pl-c1">REG ADD HKLM\SYSTEM\CurrentControlSet\Services\IPSec /v AssumeUDPEncapsulationContextOnSendRule /t REG_DWORD /d 0x2 /f</span></pre></div>
</li>
</ul>
<p>另外，某些个别的 Windows 系统配置禁用了 IPsec 加密，此时也会导致连接失败。要重新启用它，可以运行以下命令并重启。</p>
<ul>
<li>
<p>适用于 Windows XP, Vista, 7, 8.x 和 10 (<a href="https://static.ls20.com/reg-files/v1/Fix_VPN_Error_809_Allow_IPsec_Reboot_Required.reg" rel="nofollow">下载 .reg 文件</a>)</p>
<div class="highlight highlight-text-shell-session"><pre><span class="pl-c1">REG ADD HKLM\SYSTEM\CurrentControlSet\Services\RasMan\Parameters /v ProhibitIpSec /t REG_DWORD /d 0x0 /f</span></pre></div>
</li>
</ul>
<h3><a id="user-content-windows-错误-628" class="anchor" aria-hidden="true" href="#windows-错误-628"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 错误 628</h3>
<blockquote>
<p>在连接完成前，连接被远程计算机终止。</p>
</blockquote>
<p>要解决此错误，请按以下步骤操作：</p>
<ol>
<li>右键单击系统托盘中的无线/网络图标，选择 <strong>打开网络和共享中心</strong>。</li>
<li>单击左侧的 <strong>更改适配器设置</strong>。右键单击新的 VPN 连接，并选择 <strong>属性</strong>。</li>
<li>单击 <strong>安全</strong> 选项卡，从 <strong>VPN 类型</strong> 下拉菜单中选择 "使用 IPsec 的第 2 层隧道协议 (L2TP/IPSec)"。</li>
<li>单击 <strong>允许使用这些协议</strong>。确保选中 "质询握手身份验证协议 (CHAP)" 复选框。</li>
<li>单击 <strong>高级设置</strong> 按钮。</li>
<li>单击 <strong>使用预共享密钥作身份验证</strong> 并在 <strong>密钥</strong> 字段中输入<code>你的 VPN IPsec PSK</code>。</li>
<li>单击 <strong>确定</strong> 关闭 <strong>高级设置</strong>。</li>
<li>单击 <strong>确定</strong> 保存 VPN 连接的详细信息。</li>
</ol>
<p><a target="_blank" rel="noopener noreferrer" href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/images/vpn-properties-zh.png"><img src="/hwdsl2/setup-ipsec-vpn/raw/master/docs/images/vpn-properties-zh.png" alt="Select CHAP in VPN connection properties" style="max-width:100%;"></a></p>
<h3><a id="user-content-windows-10-升级" class="anchor" aria-hidden="true" href="#windows-10-升级"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 10 升级</h3>
<p>在升级 Windows 10 版本之后 （比如从 1709 到 1803），你可能需要重新按照上面的 <a href="#windows-%E9%94%99%E8%AF%AF-809">Windows 错误 809</a> 中的步骤修改注册表并重启。</p>
<h3><a id="user-content-windows-810-dns-泄漏" class="anchor" aria-hidden="true" href="#windows-810-dns-泄漏"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Windows 8/10 DNS 泄漏</h3>
<p>Windows 8.x 和 10 默认使用 "smart multi-homed name resolution" （智能多宿主名称解析）。如果你的因特网适配器的 DNS 服务器在本地网段上，在使用 Windows 自带的 IPsec VPN 客户端时可能会导致 "DNS 泄漏"。要解决这个问题，你可以 <a href="https://www.neowin.net/news/guide-prevent-dns-leakage-while-using-a-vpn-on-windows-10-and-windows-8/" rel="nofollow">禁用智能多宿主名称解析</a>，或者配置你的因特网适配器以使用在你的本地网段之外的 DNS 服务器（比如 8.8.8.8 和 8.8.4.4）。在完成后<a href="https://support.opendns.com/hc/en-us/articles/227988627-How-to-clear-the-DNS-Cache-" rel="nofollow">清除 DNS 缓存</a>并且重启计算机。</p>
<p>另外，如果你的计算机启用了 IPv6，所有的 IPv6 流量（包括 DNS 请求）都将绕过 VPN。要在 Windows 上禁用 IPv6，请看<a href="https://support.microsoft.com/zh-cn/help/929852/guidance-for-configuring-ipv6-in-windows-for-advanced-users" rel="nofollow">这里</a>。</p>
<h3><a id="user-content-macos-vpn-流量" class="anchor" aria-hidden="true" href="#macos-vpn-流量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>macOS VPN 流量</h3>
<p>OS X (macOS) 用户： 如果你成功地使用 IPsec/L2TP 模式连接，但是你的公有 IP 没有显示为 <code>你的 VPN 服务器 IP</code>，请阅读上面的 <a href="#os-x">OS X</a> 部分并完成这一步：单击 <strong>高级</strong> 按钮，并选中 <strong>通过VPN连接发送所有通信</strong> 复选框。然后重新连接 VPN。</p>
<h3><a id="user-content-iosandroid-睡眠模式" class="anchor" aria-hidden="true" href="#iosandroid-睡眠模式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>iOS/Android 睡眠模式</h3>
<p>为了节约电池，iOS 设备 (iPhone/iPad) 在屏幕变黑（睡眠模式）之后不久就会自动断开 Wi-Fi 连接。这会导致 IPsec VPN 断开。该行为是被 <a href="https://discussions.apple.com/thread/2333948" rel="nofollow">故意设计的</a> 并且不能被配置。如果你需要 VPN 在设备唤醒后自动重连，可以另外尝试使用 <a href="https://github.com/Nyr/openvpn-install">OpenVPN</a>，它支持 <a href="https://docs.openvpn.net/connecting/connecting-to-access-server-with-apple-ios/faq-regarding-openvpn-connect-ios/" rel="nofollow">一些选项</a> 比如 "Reconnect on Wakeup" 和 "Seamless Tunnel"。</p>
<p>Android 设备在进入睡眠模式不久后也会断开 Wi-Fi 连接，如果你没有启用选项 "睡眠期间保持 WLAN 开启" 的话。该选项在 Android 8 (Oreo) 中不再可用。 另外，你也可以尝试打开 "始终开启 VPN" 选项以保持连接。详情请看 <a href="https://support.google.com/android/answer/9089766?hl=zh-Hans" rel="nofollow">这里</a>。</p>
<h3><a id="user-content-android-6-及以上版本" class="anchor" aria-hidden="true" href="#android-6-及以上版本"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Android 6 及以上版本</h3>
<p>如果你无法使用 Android 6 或以上版本连接：</p>
<ol>
<li>单击 VPN 连接旁边的设置按钮，选择 "Show advanced options" 并且滚动到底部。如果选项 "Backward compatible mode" 存在（看下图），请启用它并重试连接。如果不存在，请尝试下一步。</li>
<li>编辑 VPN 服务器上的 <code>/etc/ipsec.conf</code>。找到 <code>sha2-truncbug=yes</code> 并将它替换为 <code>sha2-truncbug=no</code>。保存修改并运行 <code>service ipsec restart</code> (<a href="https://libreswan.org/wiki/FAQ#Configuration_Matters" rel="nofollow">参见</a>)</li>
</ol>
<p><a target="_blank" rel="noopener noreferrer" href="/hwdsl2/setup-ipsec-vpn/blob/master/docs/images/vpn-profile-Android.png"><img src="/hwdsl2/setup-ipsec-vpn/raw/master/docs/images/vpn-profile-Android.png" alt="Android VPN workaround" style="max-width:100%;"></a></p>
<h3><a id="user-content-chromebook-连接问题" class="anchor" aria-hidden="true" href="#chromebook-连接问题"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Chromebook 连接问题</h3>
<p>Chromebook 用户： 如果你无法连接，请尝试以下步骤：编辑 VPN 服务器上的 <code>/etc/ipsec.conf</code>。找到这一行 <code>phase2alg=...</code> 并在结尾加上 <code>,aes_gcm-null</code> 。保存修改并运行 <code>service ipsec restart</code>。</p>
<h3><a id="user-content-其它错误" class="anchor" aria-hidden="true" href="#其它错误"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>其它错误</h3>
<p>如果你遇到其它错误，请参见以下链接：</p>
<ul>
<li><a href="http://www.tp-link.com/en/faq-1029.html" rel="nofollow">http://www.tp-link.com/en/faq-1029.html</a></li>
<li><a href="https://documentation.meraki.com/MX-Z/Client_VPN/Troubleshooting_Client_VPN#Common_Connection_Issues" rel="nofollow">https://documentation.meraki.com/MX-Z/Client_VPN/Troubleshooting_Client_VPN#Common_Connection_Issues</a></li>
<li><a href="https://blogs.technet.microsoft.com/rrasblog/2009/08/12/troubleshooting-common-vpn-related-errors/" rel="nofollow">https://blogs.technet.microsoft.com/rrasblog/2009/08/12/troubleshooting-common-vpn-related-errors/</a></li>
</ul>
<h3><a id="user-content-额外的步骤" class="anchor" aria-hidden="true" href="#额外的步骤"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>额外的步骤</h3>
<p>请尝试下面这些额外的故障排除步骤：</p>
<p>首先，重启 VPN 服务器上的相关服务：</p>
<div class="highlight highlight-source-shell"><pre>service ipsec restart
service xl2tpd restart</pre></div>
<p>如果你使用 Docker，请运行 <code>docker restart ipsec-vpn-server</code>。</p>
<p>然后重启你的 VPN 客户端设备，并重试连接。如果仍然无法连接，可以尝试删除并重新创建 VPN 连接，按照本文档中的步骤操作。请确保输入了正确的 VPN 登录凭证。</p>
<p>检查 Libreswan (IPsec) 和 xl2tpd 日志是否有错误：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Ubuntu &amp; Debian</span>
grep pluto /var/log/auth.log
grep xl2tpd /var/log/syslog

<span class="pl-c"><span class="pl-c">#</span> CentOS &amp; RHEL</span>
grep pluto /var/log/secure
grep xl2tpd /var/log/messages</pre></div>
<p>查看 IPsec VPN 服务器状态：</p>
<div class="highlight highlight-source-shell"><pre>ipsec status
ipsec verify</pre></div>
<p>显示当前已建立的 VPN 连接：</p>
<div class="highlight highlight-source-shell"><pre>ipsec whack --trafficstatus</pre></div>
<h2><a id="user-content-使用命令行配置-linux-vpn-客户端" class="anchor" aria-hidden="true" href="#使用命令行配置-linux-vpn-客户端"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>使用命令行配置 Linux VPN 客户端</h2>
<p>以下步骤是基于 <a href="https://gist.github.com/psanford/42c550a1a6ad3cb70b13e4aaa94ddb1c">Peter Sanford 的工作</a>。这些命令必须在你的 VPN 客户端上使用 <code>root</code> 账户运行。</p>
<p>要配置 VPN 客户端，首先安装以下软件包：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Ubuntu &amp; Debian</span>
apt-get update
apt-get -y install strongswan xl2tpd

<span class="pl-c"><span class="pl-c">#</span> CentOS &amp; RHEL</span>
yum -y install epel-release
yum --enablerepo=epel -y install strongswan xl2tpd

<span class="pl-c"><span class="pl-c">#</span> Fedora</span>
yum -y install strongswan xl2tpd</pre></div>
<p>创建 VPN 变量 （替换为你自己的值）：</p>
<div class="highlight highlight-source-shell"><pre>VPN_SERVER_IP=<span class="pl-s"><span class="pl-pds">'</span>你的VPN服务器IP<span class="pl-pds">'</span></span>
VPN_IPSEC_PSK=<span class="pl-s"><span class="pl-pds">'</span>你的IPsec预共享密钥<span class="pl-pds">'</span></span>
VPN_USER=<span class="pl-s"><span class="pl-pds">'</span>你的VPN用户名<span class="pl-pds">'</span></span>
VPN_PASSWORD=<span class="pl-s"><span class="pl-pds">'</span>你的VPN密码<span class="pl-pds">'</span></span></pre></div>
<p>配置 strongSwan：</p>
<div class="highlight highlight-source-shell"><pre>cat <span class="pl-k">&gt;</span> /etc/ipsec.conf <span class="pl-s"><span class="pl-k">&lt;&lt;</span><span class="pl-k">EOF</span></span>
<span class="pl-s"># ipsec.conf - strongSwan IPsec configuration file</span>
<span class="pl-s"></span>
<span class="pl-s"># basic configuration</span>
<span class="pl-s"></span>
<span class="pl-s">config setup</span>
<span class="pl-s">  # strictcrlpolicy=yes</span>
<span class="pl-s">  # uniqueids = no</span>
<span class="pl-s"></span>
<span class="pl-s"># Add connections here.</span>
<span class="pl-s"></span>
<span class="pl-s"># Sample VPN connections</span>
<span class="pl-s"></span>
<span class="pl-s">conn %default</span>
<span class="pl-s">  ikelifetime=60m</span>
<span class="pl-s">  keylife=20m</span>
<span class="pl-s">  rekeymargin=3m</span>
<span class="pl-s">  keyingtries=1</span>
<span class="pl-s">  keyexchange=ikev1</span>
<span class="pl-s">  authby=secret</span>
<span class="pl-s">  ike=aes128-sha1-modp2048!</span>
<span class="pl-s">  esp=aes128-sha1-modp2048!</span>
<span class="pl-s"></span>
<span class="pl-s">conn myvpn</span>
<span class="pl-s">  keyexchange=ikev1</span>
<span class="pl-s">  left=%defaultroute</span>
<span class="pl-s">  auto=add</span>
<span class="pl-s">  authby=secret</span>
<span class="pl-s">  type=transport</span>
<span class="pl-s">  leftprotoport=17/1701</span>
<span class="pl-s">  rightprotoport=17/1701</span>
<span class="pl-s">  right=$VPN_SERVER_IP</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

cat <span class="pl-k">&gt;</span> /etc/ipsec.secrets <span class="pl-s"><span class="pl-k">&lt;&lt;</span><span class="pl-k">EOF</span></span>
<span class="pl-s">: PSK "$VPN_IPSEC_PSK"</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

chmod 600 /etc/ipsec.secrets

<span class="pl-c"><span class="pl-c">#</span> For CentOS/RHEL &amp; Fedora ONLY</span>
mv /etc/strongswan/ipsec.conf /etc/strongswan/ipsec.conf.old <span class="pl-k">2&gt;</span>/dev/null
mv /etc/strongswan/ipsec.secrets /etc/strongswan/ipsec.secrets.old <span class="pl-k">2&gt;</span>/dev/null
ln -s /etc/ipsec.conf /etc/strongswan/ipsec.conf
ln -s /etc/ipsec.secrets /etc/strongswan/ipsec.secrets</pre></div>
<p>配置 xl2tpd：</p>
<div class="highlight highlight-source-shell"><pre>cat <span class="pl-k">&gt;</span> /etc/xl2tpd/xl2tpd.conf <span class="pl-s"><span class="pl-k">&lt;&lt;</span><span class="pl-k">EOF</span></span>
<span class="pl-s">[lac myvpn]</span>
<span class="pl-s">lns = $VPN_SERVER_IP</span>
<span class="pl-s">ppp debug = yes</span>
<span class="pl-s">pppoptfile = /etc/ppp/options.l2tpd.client</span>
<span class="pl-s">length bit = yes</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

cat <span class="pl-k">&gt;</span> /etc/ppp/options.l2tpd.client <span class="pl-s"><span class="pl-k">&lt;&lt;</span><span class="pl-k">EOF</span></span>
<span class="pl-s">ipcp-accept-local</span>
<span class="pl-s">ipcp-accept-remote</span>
<span class="pl-s">refuse-eap</span>
<span class="pl-s">require-chap</span>
<span class="pl-s">noccp</span>
<span class="pl-s">noauth</span>
<span class="pl-s">mtu 1280</span>
<span class="pl-s">mru 1280</span>
<span class="pl-s">noipdefault</span>
<span class="pl-s">defaultroute</span>
<span class="pl-s">usepeerdns</span>
<span class="pl-s">connect-delay 5000</span>
<span class="pl-s">name $VPN_USER</span>
<span class="pl-s">password $VPN_PASSWORD</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

chmod 600 /etc/ppp/options.l2tpd.client</pre></div>
<p>至此 VPN 客户端配置已完成。按照下面的步骤进行连接。</p>
<p><strong>注：</strong> 当你每次尝试连接到 VPN 时，必须重复下面的所有步骤。</p>
<p>创建 xl2tpd 控制文件：</p>
<div class="highlight highlight-source-shell"><pre>mkdir -p /var/run/xl2tpd
touch /var/run/xl2tpd/l2tp-control</pre></div>
<p>重启服务：</p>
<div class="highlight highlight-source-shell"><pre>service strongswan restart
service xl2tpd restart</pre></div>
<p>开始 IPsec 连接：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Ubuntu &amp; Debian</span>
ipsec up myvpn

<span class="pl-c"><span class="pl-c">#</span> CentOS/RHEL &amp; Fedora</span>
strongswan up myvpn</pre></div>
<p>开始 L2TP 连接：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>c myvpn<span class="pl-pds">"</span></span> <span class="pl-k">&gt;</span> /var/run/xl2tpd/l2tp-control</pre></div>
<p>运行 <code>ifconfig</code> 并且检查输出。现在你应该看到一个新的网络接口 <code>ppp0</code>。</p>
<p>检查你现有的默认路由：</p>
<div class="highlight highlight-source-shell"><pre>ip route</pre></div>
<p>在输出中查找以下行： <code>default via X.X.X.X ...</code>。记下这个网关 IP，并且在下面的两个命令中使用。</p>
<p>从新的默认路由中排除你的 VPN 服务器 IP （替换为你自己的值）：</p>
<div class="highlight highlight-source-shell"><pre>route add 你的VPN服务器IP gw X.X.X.X</pre></div>
<p>如果你的 VPN 客户端是一个远程服务器，则必须从新的默认路由中排除你的本地电脑的公有 IP，以避免 SSH 会话被断开 （替换为<a href="https://www.ipchicken.com" rel="nofollow">实际值</a>）：</p>
<div class="highlight highlight-source-shell"><pre>route add 你的本地电脑的公有IP gw X.X.X.X</pre></div>
<p>添加一个新的默认路由，并且开始通过 VPN 服务器发送数据：</p>
<div class="highlight highlight-source-shell"><pre>route add default dev ppp0</pre></div>
<p>至此 VPN 连接已成功完成。检查 VPN 是否正常工作：</p>
<div class="highlight highlight-source-shell"><pre>wget -qO- http://ipv4.icanhazip.com<span class="pl-k">;</span> <span class="pl-c1">echo</span></pre></div>
<p>以上命令应该返回 <code>你的 VPN 服务器 IP</code>。</p>
<p>要停止通过 VPN 服务器发送数据：</p>
<div class="highlight highlight-source-shell"><pre>route del default dev ppp0</pre></div>
<p>要断开连接：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> Ubuntu &amp; Debian</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>d myvpn<span class="pl-pds">"</span></span> <span class="pl-k">&gt;</span> /var/run/xl2tpd/l2tp-control
ipsec down myvpn

<span class="pl-c"><span class="pl-c">#</span> CentOS/RHEL &amp; Fedora</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>d myvpn<span class="pl-pds">"</span></span> <span class="pl-k">&gt;</span> /var/run/xl2tpd/l2tp-control
strongswan down myvpn</pre></div>
<h2><a id="user-content-致谢" class="anchor" aria-hidden="true" href="#致谢"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>致谢</h2>
<p>本文档是在 <a href="https://github.com/StreisandEffect/streisand">Streisand</a> 项目文档基础上翻译和修改。该项目由 Joshua Lund 和其他开发者维护。</p>
<h2><a id="user-content-授权协议" class="anchor" aria-hidden="true" href="#授权协议"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>授权协议</h2>
<p>注： 这个协议仅适用于本文档。</p>
<p>版权所有 (C) 2016-2019 Lin Song<br>
基于 <a href="https://github.com/StreisandEffect/streisand/blob/6aa6b6b2735dd829ca8c417d72eb2768a89b6639/playbooks/roles/l2tp-ipsec/templates/instructions.md.j2">Joshua Lund 的工作</a> (版权所有 2014-2016)</p>
<p>本程序为自由软件，在自由软件联盟发布的<a href="https://www.gnu.org/licenses/gpl.html" rel="nofollow"> GNU 通用公共许可协议</a>的约束下，你可以对其进行再发布及修改。协议版本为第三版或（随你）更新的版本。</p>
<p>我们希望发布的这款程序有用，但不保证，甚至不保证它有经济价值和适合特定用途。详情参见GNU通用公共许可协议。</p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2019 <span title="0.16056s from unicorn-5f6f547777-ns9nm">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-eYWkirt5BXd8Z6IvLT/AkE0jvsyFHbTICcEN1Aczj9caa8b+20ToUYPgohknnTlFrLElgEN0HX9Oh8XHbTFNBw==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-4199e113.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-v7DMdD9nOupolgEznyVt6jkYstlmhvl+WlRiHpi6EdRe8FYBp4yK+yEKrghaofifa3x8sXCtV4yy04U0d6fdFg==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-80470f8d.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark" open>
    <summary aria-haspopup="dialog" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

