<!DOCTYPE html>
<html data-ui-framework="dust" lang="en" data-presentation-type="FULL_PAGE" class="theme--artdeco">

<head>
    <link rel="stylesheet" href="https://static-exp1.licdn.com/sc/h/73wtdp5k6lh2bx29c502uhjhz" />
    <link rel="stylesheet" href="https://static-exp1.licdn.com/sc/h/es8i2wdgafxiuslgc5gm2j943" disabled="disabled" id="ui-theme-mercado" />
    <link rel="stylesheet" href="https://static-exp1.licdn.com/sc/h/c4s0q0e2w5czaii2je7ddhycx" disabled="disabled" id="ui-theme-dark" />
    <script src="https://static.licdn.com:443/scds/common/u/lib/fizzy/fz-1.3.8-min.js" type="text/javascript"></script>
    <script type="text/javascript">
        fs.config({
            "failureRedirect": "http://www.linkedin.com/",
            "uniEscape": true,
            "xhrHeaders": {
                "X-FS-Origin-Request": "/help/linkedin",
                "X-FS-Page-Id": "d_hc_home"
            }
        });
    </script>
    <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/ebqsvn2mke2qg3b7dz0ucfh3m"></script>
    <link rel="icon" href="//static.licdn.com/scds/common/u/images/logos/favicons/v1/favicon.ico">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="apple-mobile-web-app-capable" content="yes" />
    <meta name="apple-mobile-web-app-status-bar-style" content="default" />
    <title></title>
    <meta content="" name="og:title">
    <meta content="" name="og:site_name">
    <meta content="" name="description">
    <meta content="" name="og:description">
    <meta content="" name="robots">
    <link rel="canonical" href="" />
    <meta content="" name="og:url">
</head>

<body class='product-linkedin has-search-banner' id="pagekey-hc_home">
    <div class="hc-body" id="application-body">
        <div class="global-wrapper hc-page"><code id="__pageContext__" style="display: none;"><!--{"baseScdsUrl":"https://static-exp1.licdn.com/scds","contextPath":"/help","pageInstance":"urn:li:page:hc_home;yu1MlgzJSUeuE7mjkKCHuA==","isProd":true,"brotliBaseSparkUrlForHashes":"https://static-exp1.licdn.com/sc/h","linkedInDustJsUrl":"https://static-exp1.licdn.com/sc/h/ebqsvn2mke2qg3b7dz0ucfh3m","baseSparkUrlForHashes":"https://static-exp1.licdn.com/sc/h","isCsUser":false,"appName":"helpcenter-frontend","fizzyJsUrl":"https://static-exp1.licdn.com/scds/common/u/lib/fizzy/fz-1.3.3-min.js","mpName":"helpcenter","scHashesUrl":"https://static-exp1.licdn.com/sc/h/29rek1ixq7tusgyxvtnc7wce","dustDebug":"NONE","baseMediaUrl":"https://media-exp1.licdn.com/media","isBrotliEnabled":false,"useCdn":true,"locale":"en_US","version":"0.5.828","useScHashesJs":true,"cdnUrl":"https://static-exp1.licdn.com","baseMprUrl":"https://media-exp1.licdn.com/mpr/mpr","playUtilsUrl":"https://static-exp1.licdn.com/sc/h/9ebuc4j580bqpof7u5yzszuh6","useNativeXmsg":false,"hashesDisabledByQueryParam":false,"baseAssetsUrl":"https://static-exp1.licdn.com/sc/p/com.linkedin.helpcenter%3Ahelpcenter-static-content%2B0.5.828/f","csrfToken":"ajax:7471867477961617209","intlPolyfillUrl":"https://static-exp1.licdn.com/sc/h/cnl4ds6k7892dt3v85qv5108y","serveT8WithDust":false,"disableDynamicConcat":true,"baseSparkUrlForFiles":"https://static-exp1.licdn.com/sc/p/com.linkedin.helpcenter%3Ahelpcenter-static-content%2B0.5.828/f","dustUtilsUrl":"https://static-exp1.licdn.com/sc/h/5ildxgqmsir5o48f76ealt1pv","linkedInDustI18nJsUrl":"https://static-exp1.licdn.com/sc/h/3aqzgvxgckdcy547thi000u9c","baseMediaProxyUrl":"https://media-exp1.licdn.com/media-proxy"}--></code>
            <script
                src="https://static-exp1.licdn.com/sc/h/29rek1ixq7tusgyxvtnc7wce"></script>
                <script src="https://static-exp1.licdn.com/sc/h/5ildxgqmsir5o48f76ealt1pv"></script>
                <script>
                    (function(root) {
                        var jsRoutes = {};
                        (function(_root) {
                            var _nS = function(c, f, b) {
                                var e = c.split(f || "."),
                                    g = b || _root,
                                    d, a;
                                for (d = 0, a = e.length; d < a; d++) {
                                    g = g[e[d]] = g[e[d]] || {}
                                }
                                return g
                            }
                            var _qS = function(items) {
                                var qs = '';
                                for (var i = 0; i < items.length; i++) {
                                    if (items[i]) qs += (qs ? '&' : '') + items[i]
                                };
                                return qs ? ('?' + qs) : ''
                            }
                            var _s = function(p, s) {
                                return p + ((s === true || (s && s.secure)) ? 's' : '') + '://'
                            }
                            var _wA = function(r) {
                                return {
                                    ajax: function(c) {
                                        c = c || {};
                                        c.url = r.url;
                                        c.type = r.method;
                                        return jQuery.ajax(c)
                                    },
                                    method: r.method,
                                    type: r.method,
                                    url: r.url,
                                    absoluteURL: function(s) {
                                        return _s('http', s) + 'www.linkedin.com' + r.url
                                    },
                                    webSocketURL: function(s) {
                                        return _s('ws', s) + 'www.linkedin.com' + r.url
                                    }
                                }
                            }
                            _nS('controllers.api.Answer');
                            _root['controllers']['api']['Answer']['rateTranslation'] =
                                function(hc_product0, articleId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/answer/rate-translation/" + (function(k, v) {
                                            return v
                                        })("articleId", articleId1)
                                    })
                                };
                            _nS('controllers.Forum');
                            _root['controllers']['Forum']['ask'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/forum/ask"
                                    })
                                };
                            _nS('controllers.Topic');
                            _root['controllers']['Topic']['versionedTopic'] =
                                function(hcInstance0, topicId1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hcInstance", hcInstance0)) + "/topic/" + (function(k, v) {
                                            return v
                                        })("topicId", topicId1)
                                    })
                                };
                            _nS('controllers.api.Attachments');
                            _root['controllers']['api']['Attachments']['upload'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/attachments/upload"
                                    })
                                };
                            _nS('controllers.api.Ticket');
                            _root['controllers']['api']['Ticket']['reopen'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tickets/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1)) + "/reopen"
                                    })
                                };
                            _nS('controllers.api.Topics');
                            _root['controllers']['api']['Topics']['topic'] =
                                function(hc_product0, p_id1, b_id2) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/topics/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("b_id", b_id2))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['addComment'] =
                                function(hc_product0, nodeType1, nodeId2) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/comment/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeType", nodeType1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId2))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['nodeOperation'] =
                                function(hc_product0, nodeOp1, nodeId2, nodeType3) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeOp", nodeOp1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId2)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeType", nodeType3))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['questionDetail'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/question/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1))
                                    })
                                };
                            _nS('controllers.api.Answer');
                            _root['controllers']['api']['Answer']['detail'] =
                                function(hc_product0, a_id1, lang2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/api/answer/" + (function(k, v) {
                                                return v
                                            })("a_id", a_id1) + _qS([(lang2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("lang", lang2))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Client');
                            _root['controllers']['api']['Client']['getOpenCases'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/opencases"
                                    })
                                };
                            _nS('controllers.Cases');
                            _root['controllers']['Cases']['detail'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/cases/" + (function(k, v) {
                                            return v
                                        })("id", id1)
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['adminOperation'] =
                                function(hc_product0, adminOp1, memberId2) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("adminOp", adminOp1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("memberId", memberId2))
                                    })
                                };
                            _nS('controllers.BrowseTopics');
                            _root['controllers']['BrowseTopics']['suggested'] =
                                function(hc_product0, id1, title2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/suggested/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("id", id1)) + _qS([(title2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title2))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['getSuggestions'] =
                                function(hc_product0, query1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/suggestions/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("query", query1))
                                    })
                                };
                            _nS('controllers.Answer');
                            _root['controllers']['Answer']['articlePreview'] =
                                function(hc_product0, articleId1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/answer-preview/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("articleId", articleId1))
                                    })
                                };
                            _nS('controllers.api.ContactUs');
                            _root['controllers']['api']['ContactUs']['trackContactViewEvent'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/contactUs/track/trackContactView"
                                    })
                                };
                            _nS('controllers.Answer');
                            _root['controllers']['Answer']['search'] =
                                function(hc_product0, query1, page2) {

                                    if (page2 == 1) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/answers/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("query", query1))
                                        })
                                    }

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/answers/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("query", query1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("page", page2))
                                        })
                                    }

                                };
                            _nS('controllers.BrowseTopics');
                            _root['controllers']['BrowseTopics']['topic'] =
                                function(hc_product0, p_id1, b_id2, title3) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/topics/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("b_id", b_id2)) + _qS([(title3 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title3))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Answer');
                            _root['controllers']['api']['Answer']['rate'] =
                                function(hc_product0, articleId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/answer/rate/" + (function(k, v) {
                                            return v
                                        })("articleId", articleId1)
                                    })
                                };
                            _nS('controllers.api.MobileApps');
                            _root['controllers']['api']['MobileApps']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/mobile-apps/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("b_id", b_id2)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("a_id", a_id3))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['addAnswer'] =
                                function(hc_product0, nodeId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/answer/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['getNode'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/node/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1))
                                    })
                                };
                            _nS('controllers.api.Tracking');
                            _root['controllers']['api']['Tracking']['entityView'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tracking/entity"
                                    })
                                };
                            _nS('controllers.api.Chat');
                            _root['controllers']['api']['Chat']['available'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/chat/available"
                                    })
                                };
                            _nS('com.linkedin.helpcenter.chatbot.ChatBotController');
                            _root['com']['linkedin']['helpcenter']['chatbot']['ChatBotController']['redirectToFlagshipSearch'] =
                                function(hc_product0, segment1, query2, interactedOptionNum3) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/interactive-search/search-on-linkedin/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("segment", segment1)) + _qS([(function(k, v) {
                                            return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                        })("query", query2), (function(k, v) {
                                            return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                        })("interactedOptionNum", interactedOptionNum3)])
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['nodeQuestionOperation'] =
                                function(hc_product0, nodeOp1, questionId2, nodeId3) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeOp", nodeOp1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("questionId", questionId2)) + "/" + (function(k, v) {
                                            return v
                                        })("nodeId", nodeId3)
                                    })
                                };
                            _nS('controllers.api.Tracking');
                            _root['controllers']['api']['Tracking']['homeView'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tracking/home"
                                    })
                                };
                            _nS('controllers.api.Billing');
                            _root['controllers']['api']['Billing']['topicGroup'] =
                                function(hc_product0, p_id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/billing/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1))
                                    })
                                };
                            _nS('controllers.api.Answer');
                            _root['controllers']['api']['Answer']['popular'] =
                                function(hc_product0, limit1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/answers/popular/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("limit", limit1))
                                    })
                                };
                            _nS('controllers.Billing');
                            _root['controllers']['Billing']['topicGroup'] =
                                function(hc_product0, p_id1, title2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/billing/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + _qS([(title2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title2))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Tracking');
                            _root['controllers']['api']['Tracking']['genericView'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tracking/generic"
                                    })
                                };
                            _nS('controllers.Cases');
                            _root['controllers']['Cases']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/cases"
                                    })
                                };
                            _nS('controllers.Billing');
                            _root['controllers']['Billing']['topic'] =
                                function(hc_product0, p_id1, b_id2, title3) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/billing/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + (function(k, v) {
                                                return v
                                            })("b_id", b_id2) + _qS([(title3 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title3))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Ticket');
                            _root['controllers']['api']['Ticket']['close'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tickets/" + (function(k, v) {
                                            return v
                                        })("id", id1) + "/close"
                                    })
                                };
                            _nS('controllers.ContactUs');
                            _root['controllers']['ContactUs']['thankYou'] =
                                function(hc_product0, id1) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/thankyou" + _qS([(id1 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("id", id1))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['updateQuestion'] =
                                function(hc_product0, nodeId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/update/question/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1))
                                    })
                                };
                            _nS('controllers.Answer');
                            _root['controllers']['Answer']['detail'] =
                                function(hc_product0, id1, title2, contentLang3) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/answer/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("id", id1)) + _qS([(title2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title2)), (contentLang3 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("contentLang", contentLang3))])
                                        })
                                    }

                                };
                            _nS('controllers.api.ContactUs');
                            _root['controllers']['api']['ContactUs']['trackWebFormViewEvent'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/contactUs/track/trackwebFormView"
                                    })
                                };
                            _nS('controllers.api.Topics');
                            _root['controllers']['api']['Topics']['topicGroup'] =
                                function(hc_product0, p_id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/topics/" + (function(k, v) {
                                            return v
                                        })("p_id", p_id1)
                                    })
                                };
                            _nS('controllers.api.Chat');
                            _root['controllers']['api']['Chat']['sessionProgress'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/chat/sessionProgress"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['getAnswers'] =
                                function(hc_product0, nodeId1, page2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/api/forum/answers/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("nodeId", nodeId1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("page", page2))
                                        })
                                    }

                                };
                            _nS('controllers.api.Answer');
                            _root['controllers']['api']['Answer']['feedback'] =
                                function(hc_product0, articleId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/answer/" + (function(k, v) {
                                            return v
                                        })("articleId", articleId1) + "/feedback"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['convertQuestionToCase'] =
                                function(hc_product0, nodeId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/convert/question/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1))
                                    })
                                };
                            _nS('controllers.api.Chat');
                            _root['controllers']['api']['Chat']['interaction'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/chat/interaction"
                                    })
                                };
                            _nS('controllers.api.ContactUs');
                            _root['controllers']['api']['ContactUs']['trackSmartAssistClickEvent'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/contactUs/track/smartAssistClick"
                                    })
                                };
                            _nS('controllers.MobileApps');
                            _root['controllers']['MobileApps']['topic'] =
                                function(hc_product0, p_id1, b_id2, title3) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/mobile-apps/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + (function(k, v) {
                                                return v
                                            })("b_id", b_id2) + _qS([(title3 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title3))])
                                        })
                                    }

                                };
                            _nS('controllers.Forum');
                            _root['controllers']['Forum']['questionDetail'] =
                                function(hc_product0, id1, title2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/forum/question/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("id", id1)) + _qS([(title2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title2))])
                                        })
                                    }

                                };
                            _nS('com.linkedin.helpcenter.frontend.featurelaunchers.FeatureLauncherController');
                            _root['com']['linkedin']['helpcenter']['frontend']['featurelaunchers']['FeatureLauncherController']['redirect'] =
                                function(hcInstance0, source1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hcInstance", hcInstance0)) + "/feature-launcher/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("source", source1))
                                    })
                                };
                            _nS('controllers.api.Attachments');
                            _root['controllers']['api']['Attachments']['download'] =
                                function(hc_product0, ticketId1, fileId2) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/attachments/download/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("ticketId", ticketId1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("fileId", fileId2))
                                    })
                                };
                            _nS('controllers.api.Chat');
                            _root['controllers']['api']['Chat']['clickToCallAvailable'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/chat/clickToCallAvailable"
                                    })
                                };
                            _nS('controllers.BrowseTopics');
                            _root['controllers']['BrowseTopics']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3, title4) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/topics/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("b_id", b_id2)) + "/" + (function(k, v) {
                                                return v
                                            })("a_id", a_id3) + _qS([(title4 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title4))])
                                        })
                                    }

                                };
                            _nS('controllers.Billing');
                            _root['controllers']['Billing']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3, title4) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/billing/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("b_id", b_id2)) + "/" + (function(k, v) {
                                                return v
                                            })("a_id", a_id3) + _qS([(title4 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title4))])
                                        })
                                    }

                                };
                            _nS('controllers.Forum');
                            _root['controllers']['Forum']['index'] =
                                function(hc_product0, sort1, page2, filters3, query4) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/forum" + _qS([(sort1 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("sort", sort1)), (page2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("page", page2)), (filters3 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("filters", filters3)), (function(k, v) {
                                                return v != null ? (function(k, v) {
                                                    return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                                })(k, v) : ''
                                            })("query", query4)])
                                        })
                                    }

                                };
                            _nS('controllers.api.Topics');
                            _root['controllers']['api']['Topics']['popular'] =
                                function(hc_product0, referer1) {

                                    if (referer1 == "") {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/api/topics"
                                        })
                                    }

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/api/topics/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("referer", referer1))
                                        })
                                    }

                                };
                            _nS('com.linkedin.helpcenter.frontend.typeahead.SuggestedSearchTermsController');
                            _root['com']['linkedin']['helpcenter']['frontend']['typeahead']['SuggestedSearchTermsController']['suggestedSearchTerms'] =
                                function(hc_product0, query1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/suggestedSearch/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("query", query1))
                                    })
                                };
                            _nS('controllers.api.MobileApps');
                            _root['controllers']['api']['MobileApps']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/mobile-apps"
                                    })
                                };
                            _nS('controllers.api.Billing');
                            _root['controllers']['api']['Billing']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/billing"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['convertAnswerToCase'] =
                                function(hc_product0, nodeId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/convert/answer/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1)) + "/"
                                    })
                                };
                            _nS('controllers.Billing');
                            _root['controllers']['Billing']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/billing"
                                    })
                                };
                            _nS('controllers.api.Survey');
                            _root['controllers']['api']['Survey']['progress'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/survey/progress"
                                    })
                                };
                            _nS('controllers.MobileApps');
                            _root['controllers']['MobileApps']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3, title4) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/mobile-apps/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("b_id", b_id2)) + "/" + (function(k, v) {
                                                return v
                                            })("a_id", a_id3) + _qS([(title4 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title4))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Topics');
                            _root['controllers']['api']['Topics']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/topics/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("b_id", b_id2)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("a_id", a_id3))
                                    })
                                };
                            _nS('controllers.api.Billing');
                            _root['controllers']['api']['Billing']['entity'] =
                                function(hc_product0, p_id1, b_id2, a_id3) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/billing/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("b_id", b_id2)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("a_id", a_id3))
                                    })
                                };
                            _nS('controllers.MobileApps');
                            _root['controllers']['MobileApps']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/mobile-apps"
                                    })
                                };
                            _nS('controllers.ContactUs');
                            _root['controllers']['ContactUs']['default'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/ask"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['ask'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/ask"
                                    })
                                };
                            _nS('com.linkedin.helpcenter.chatbot.ChatBotController');
                            _root['com']['linkedin']['helpcenter']['chatbot']['ChatBotController']['redirectToFullArticlePage'] =
                                function(hc_product0, articleId1, query2, answerTitle3) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/interactive-search/full-article/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("articleId", articleId1)) + _qS([(function(k, v) {
                                            return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                        })("query", query2), (function(k, v) {
                                            return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                        })("answerTitle", answerTitle3)])
                                    })
                                };
                            _nS('com.linkedin.helpcenter.frontend.typeahead.SuggestedSearchTermsController');
                            _root['com']['linkedin']['helpcenter']['frontend']['typeahead']['SuggestedSearchTermsController']['topSearchSuggestions'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/suggestedSearch"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['convertCommentToAnswer'] =
                                function(hc_product0, nodeId1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/convert/comment/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1)) + "/"
                                    })
                                };
                            _nS('controllers.MobileApps');
                            _root['controllers']['MobileApps']['topicGroup'] =
                                function(hc_product0, p_id1, title2) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/mobile-apps/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("p_id", p_id1)) + _qS([(title2 == null ? null : (function(k, v) {
                                                return encodeURIComponent(k) + '=' + encodeURIComponent(v)
                                            })("title", title2))])
                                        })
                                    }

                                };
                            _nS('controllers.api.Topics');
                            _root['controllers']['api']['Topics']['suggested'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/suggested/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1))
                                    })
                                };
                            _nS('com.linkedin.helpcenter.chatbot.ChatBotController');
                            _root['com']['linkedin']['helpcenter']['chatbot']['ChatBotController']['captureAndTriggerFrontendTrackingEvents'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/interactive-search/trk"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['lookupForumUser'] =
                                function(hc_product0, memberId1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/forumUser/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("memberId", memberId1))
                                    })
                                };
                            _nS('controllers.api.Attachments');
                            _root['controllers']['api']['Attachments']['view'] =
                                function(hc_product0, ticketId1, fileId2) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/attachments/view/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("ticketId", ticketId1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("fileId", fileId2))
                                    })
                                };
                            _nS('controllers.api.Client');
                            _root['controllers']['api']['Client']['getRecentlyChangedCases'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/recentlychangedcases"
                                    })
                                };
                            _nS('controllers.ContactUs');
                            _root['controllers']['ContactUs']['custom'] =
                                function(hc_product0, name1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/ask/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("name", name1))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['getComments'] =
                                function(hc_product0, nodeType1, nodeId2, page3) {

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/api/forum/comments/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("nodeType", nodeType1)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("nodeId", nodeId2)) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("page", page3))
                                        })
                                    }

                                };
                            _nS('controllers.api.Ticket');
                            _root['controllers']['api']['Ticket']['comment'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tickets/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1)) + "/comments"
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['updateNode'] =
                                function(hc_product0, nodeType1, nodeId2) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/update/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeType", nodeType1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId2))
                                    })
                                };
                            _nS('controllers.api.Ticket');
                            _root['controllers']['api']['Ticket']['create'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/ticket/new"
                                    })
                                };
                            _nS('controllers.api.Geolocation');
                            _root['controllers']['api']['Geolocation']['getLocale'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/geolocation"
                                    })
                                };
                            _nS('controllers.api.MobileApps');
                            _root['controllers']['api']['MobileApps']['topicGroup'] =
                                function(hc_product0, p_id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/mobile-apps/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("p_id", p_id1))
                                    })
                                };
                            _nS('controllers.Answer');
                            _root['controllers']['Answer']['versionedArticle'] =
                                function(hc_product0, articleId1, slug2) {

                                    if (slug2 == "") {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/answer/" + (function(k, v) {
                                                return v
                                            })("articleId", articleId1)
                                        })
                                    }

                                    if (true) {
                                        return _wA({
                                            method: "GET",
                                            url: "/help/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("hc_product", hc_product0)) + "/answer/" + (function(k, v) {
                                                return v
                                            })("articleId", articleId1) + "/" + encodeURIComponent((function(k, v) {
                                                return v
                                            })("slug", slug2))
                                        })
                                    }

                                };
                            _nS('controllers.Topic');
                            _root['controllers']['Topic']['topic'] =
                                function(hc_product0, id1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/topic/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("id", id1))
                                    })
                                };
                            _nS('controllers.api.Tracking');
                            _root['controllers']['api']['Tracking']['lyndaConsentAction'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/tracking/lyndaConsent"
                                    })
                                };
                            _nS('controllers.Topic');
                            _root['controllers']['Topic']['allTopics'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/topics"
                                    })
                                };
                            _nS('controllers.api.SmartAssistant');
                            _root['controllers']['api']['SmartAssistant']['get'] =
                                function(hc_product0, query1) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/smart/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("query", query1))
                                    })
                                };
                            _nS('controllers.Home');
                            _root['controllers']['Home']['index'] =
                                function(hc_product0) {
                                    return _wA({
                                        method: "GET",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0))
                                    })
                                };
                            _nS('controllers.api.Forum');
                            _root['controllers']['api']['Forum']['convertAnswerToComment'] =
                                function(hc_product0, nodeId1, parentId2) {
                                    return _wA({
                                        method: "POST",
                                        url: "/help/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("hc_product", hc_product0)) + "/api/forum/convert/answer/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("nodeId", nodeId1)) + "/" + encodeURIComponent((function(k, v) {
                                            return v
                                        })("parentId", parentId2))
                                    })
                                };
                        })(jsRoutes);
                        root.play = root.play || {};
                        root.play.jsRoutes = root.play.jsRoutes || {};
                        var extend = function(original, context) {
                            for (key in context)
                                if (context.hasOwnProperty(key))
                                    if (Object.prototype.toString.call(context[key]) === '[object Object]')
                                        original[key] = extend(original[key] || {}, context[key]);
                                    else
                                        original[key] = context[key];
                            return original;
                        };
                        root.play.jsRoutes = extend(root.play.jsRoutes, jsRoutes);
                    })(this);
                </script>
                <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/27fmnmcuaa89882far6icoqgw"></script>
                <section id="global-sticky-header" class="hc-page__nav">
                    <div tabindex="-1" id="js-notification-wrapper" role="alert" aria-live="assertive"></div>
                    <div class="accessibility-menu js-accessibility-menu">
                        <div class="visually-hidden" aria-live="polite">
                            <p class="mobile-view-on-desktop">Attention screen reader users, you are in a mobile optimized view and content may not appear where you expect it to be. To return the screen to its desktop view, please maximize your browser.</p>
                        </div>
                        <div class="container-fluid mobile-excluded">
                            <div class="accessibility-menu__content-wrapper">
                                <div class="accessibility-menu__content"><a class="accessibility-menu__skip-link js-content-link artdeco-button artdeco-button--2 artdeco-button--secondary artdeco-button--inverse" href="#a11y-main">Skip to content</a><a class="accessibility-menu__skip-link js-content-link artdeco-button artdeco-button--2 artdeco-button--secondary artdeco-button--inverse"
                                        href="#desktop-hero-search-query">Skip to search</a></div><button class="js-dismiss artdeco-button artdeco-button--inverse artdeco-button--2 artdeco-button--circle artdeco-button--tertiary"><li-icon class="svg-icon " type="cancel-icon" size="large" color=""  tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">Close jump menu</span></button></div>
                        </div>
                    </div>
                    <header class="global-header js-top-bar">
                        <div class="global-header__nav-wrapper global-header__nav-wrapper--mobile js-global-header-mobile">
                            <nav class="mobile-nav" aria-label="Main">
                                <div class="mobile-nav__logo">
                                    <a class="brand__link" href="/help/linkedin">
                                        <li-icon class="" type="linkedin-bug" size="34dp" color="inverse" tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">LinkedIn Help</span></a>
                                </div>
                                <div class="mobile-nav__search">
                                    <form class="header-search header-search--static js-search-assist" name="main-search" role="search" action=""><label class="a11y-hidden" for="mobile-nav-search-query" aria-hidden="true">What’s your question?</label><input id="mobile-nav-search-query" data-test-id="mobile-nav-search-query" type="search" aria-hidden="false" class="header-search__input js-search-assist-input"
                                            name="search-query" placeholder='How can we help?' value="" maxlength="255" required>
                                        <div class="header-search__button-wrapper"><button class="header-search__button header-search__button--compound-search js-submit-button test-desktop-search-button" data-test-id="mobile-nav-search-button" aria-hidden="false" type="submit" aria-label='Submit your question'
                                                disabled><li-icon class="svg-icon " type="search-icon" size="small" color=""  tabindex="-1" aria-hidden="true"></li-icon></button></div>
                                    </form>
                                </div>
                                <div class="mobile-nav__me-menu">
                                    <div class="mobile-me-menu dropdown__container mobile-only"><button class="mobile-me-menu__button dropdown__trigger" data-test-id="mobile-menu-button" aria-expanded="false" aria-controls="mobile-me-menu__dropdown" aria-label="Dropdown menu, expand to explore help for other LinkedIn products"><li-icon class="" type="hamburger-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon></button>
                                        <div
                                            id="mobile-me-menu__dropdown" class="mobile-me-menu__dropdown dropdown__menu" tabindex="-1" aria-hidden="true"><button class="dropdown__close-button plain-button"><li-icon class="" type="cancel-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">Close menu</span></button>
                                            <div
                                                class="product-switcher__wrapper product-switcher--mobile">
                                                <div id="mobile-nav-product-switcher__menu" class="product-switcher__menu">
                                                    <h4 class="product-switcher__menu-header">Get help with:</h4>
                                                    <div class="product-switcher__menu-content"><a class="product-menu__link dropdown__menu-item product-menu__link--selected" href="/help/linkedin?trk=hc-product-switcher">LinkedIn</a><a class="product-menu__link dropdown__menu-item" href="/help/sales-navigator?trk=hc-product-switcher">Sales Navigator</a>
                                                        <a
                                                            class="product-menu__link dropdown__menu-item" href="/help/billing?trk=hc-product-switcher">Corporate Billing</a><a class="product-menu__link dropdown__menu-item" href="/help/recruiter?trk=hc-product-switcher">Recruiter</a><a class="product-menu__link dropdown__menu-item" href="/help/talent-hub?trk=hc-product-switcher">Talent Hub</a>
                                                            <a
                                                                class="product-menu__link dropdown__menu-item" href="/help/talent-insights?trk=hc-product-switcher">Talent Insights</a><a class="product-menu__link dropdown__menu-item" href="/help/lms?trk=hc-product-switcher">Marketing Solutions</a><a class="product-menu__link dropdown__menu-item" href="/help/sales-insights?trk=hc-product-switcher">Sales Insights</a>
                                                                <a
                                                                    class="product-menu__link dropdown__menu-item" href="/help/learning?trk=hc-product-switcher">Learning</a>
                                                    </div>
                                                </div>
                                    </div><a class="manage-menu__link mobile-me-menu__link dropdown__menu-item" href="https://www.linkedin.com/">Go to LinkedIn</a><a class="sign-in__link js-sign-in mobile-me-menu__link mobile-me-menu__link--sign-in dropdown__menu-item"
                                        href="https://www.linkedin.com/uas/login?session_redirect=http://www.linkedin.com/help/linkedin">Sign in</a><span class="visually-hidden">End of menu</span></div>
                        </div>
        </div>
        </nav>
    </div>
    <div class="global-header__nav-wrapper global-header__nav-wrapper--desktop js-global-header-desktop">
        <nav class="desktop-nav desktop-nav__compound-search" aria-label="Main">
            <div class="desktop-nav__logo">
                <a class="brand__link" href="/help/linkedin">
                    <li-icon class="" type="linkedin-bug" size="34dp" color="inverse" tabindex="-1" aria-hidden="true"></li-icon>
                    <h1 class="brand__title brand__title--compound-search" data-test-id="brand-title">Help</h1>
                </a>
            </div>
            <div class="desktop-nav__search desktop-nav__search--compound-search">
                <form class="header-search header-search--static header-search--compound header-search--compound-hidden header-search--hidden js-search-assist" name="main-search" role="search" action="">
                    <div class="compound-search-product-switcher dropdown__container"><button id="compound-search-product-switcher-trigger" class="compound-search-product-switcher__trigger dropdown__trigger" aria-controls="desktop-nav-product-switcher__menu" aria-expanded="false" aria-haspopup="listbox" aria-label="Dropdown menu for switching to searching in other help center for other LinkedIn products"
                            data-is-animating-click="true" data-test-id="product-switcher-dropdown" type="button"><div class="compound-search-product-switcher__trigger-label dropdown__trigger-label">LinkedIn Help</div><li-icon class="compound-search-product-switcher__trigger-button-caret" type="caret-filled-down-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon></button>
                        <div
                            id="desktop-nav-product-switcher__menu" class="compound-search-product-switcher__menu dropdown__menu" tabindex="-1" aria-hidden="true"><button id="compound-search-product-switcher__menu-item0" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item compound-search-product-switcher__menu-item--selected js-search-assist-selected-product"
                                value="linkedin">LinkedIn Help</button><button id="compound-search-product-switcher__menu-item1" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="sales-navigator">Sales Navigator Help</button>
                            <button
                                id="compound-search-product-switcher__menu-item2" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="billing">Corporate Billing Help</button><button id="compound-search-product-switcher__menu-item3" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="recruiter">Recruiter Help</button>
                                <button
                                    id="compound-search-product-switcher__menu-item4" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="talent-hub">Talent Hub Help</button><button id="compound-search-product-switcher__menu-item5" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="talent-insights">Talent Insights Help</button>
                                    <button
                                        id="compound-search-product-switcher__menu-item6" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="lms">Marketing Solutions Help</button><button id="compound-search-product-switcher__menu-item7" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="sales-insights">Sales Insights Help</button>
                                        <button
                                            id="compound-search-product-switcher__menu-item8" type="button" class="compound-search-product-switcher__menu-item dropdown__menu-item" value="learning">Learning Help</button>
                    </div>
            </div><label class="a11y-hidden" for="desktop-nav-search-query" aria-hidden="true">What’s your question?</label><input id="desktop-nav-search-query" data-test-id="desktop-nav-search-query" type="search" aria-hidden="false" class="header-search__compound-search-input js-search-assist-input"
                name="search-query" placeholder='How can we help?' value="" maxlength="255" required>
            <div class="header-search__button-wrapper"><button class="header-search__button header-search__button--compound-search js-submit-button test-desktop-search-button" data-test-id="desktop-nav-search-button" aria-hidden="false" type="submit" aria-label='Submit your question' disabled><li-icon class="svg-icon " type="search-icon" size="small" color=""  tabindex="-1" aria-hidden="true"></li-icon></button></div>
            </form>
    </div>
    <div class="desktop-nav__me-menu">
        <div class="desktop-me-menu dropdown__container mobile-excluded"><a class="desktop-me-menu__sign-in js-sign-in" href="https://www.linkedin.com/uas/login?session_redirect=http://www.linkedin.com/help/linkedin">Sign in</a></div>
    </div>
    </nav>
    </div>
    </header>
    </section>
    <section class="hc-page__content">
        <script src="https://static-exp1.licdn.com/sc/h/3i2lkk024cd1zr54f1lwtl6j2" id="templates/fusion/pages/homepage"></script><code id="templates/fusion/pages/homepage-content" style="display: none;"><!--{"head":{},"pageData":{"pageAside":{"ticketSupport":{"descriptionI18nKey":"i18n_common_contact_support_ticket_message_support","illustration":"mail-closed","ctaI18nKey":"i18n_common_contact_support_ticket_create_link_text","headerI18nKey":"i18n_common_contact_support_ticket_create"},"professionalCommunity":{"descriptionI18nKey":"i18n_common_our_policies_ensure","illustration":"people-conversation","ctaI18nKey":"i18n_common_learn_more","headerI18nKey":"i18n_common_professional_community_policies"},"showContactUs":true,"safetyCenter":{"descriptionI18nKey":"i18n_common_your_account_security","illustration":"lock","ctaI18nKey":"i18n_common_learn_more","headerI18nKey":"i18n_common_safety_center"},"clickToCallSupport":{"offlineIllustration":"mobile-phone-muted","onlineDescriptionI18nKey":"i18n_common_contact_support_click_to_call_online","onlineIllustration":"mobile-phone","onlineCtaI18nKey":"i18n_landing_page_contact_support_option_phone_link_text_available","inProgressDescriptionI18nKey":"i18n_common_contact_support_click_to_call_in_progress","offlineHeaderI18nKey":"i18n_popular_actions_request_phone_call_available","onlineHeaderI18nKey":"i18n_popular_actions_request_phone_call_available","offlineDescriptionI18nKey":"i18n_popular_actions_contact_option_unavailable"}}},"global":{"referralUrl":"","showClickToCall":false,"nativeConfig":{"nativeHomeId":5069,"nativeHideSearch":false,"nativeHideContact":false,"nativeHideHomeLink":false},"productParams":{"productName":"linkedin","appChooserIcon":"app-linkedin-bug-color-icon","productIcon":"linkedin","productUrl":"https://www.linkedin.com/","productType":"website"},"showChatCtcLlsUnbound":false,"isDynamicsCaseEnabled":true,"path":"/help/linkedin","showForumDriver":false,"showSafetyCenter":true,"showFusionLssCommunityLink":false,"showSurvey":true,"languageSwitcher":{"supportedLanguages":[{"languageTag":"en","rtl":false,"locale":"en_US","displayName":"English (English)"},{"languageTag":"cs","rtl":false,"locale":"cs_CZ","displayName":"Čeština (Czech)"},{"languageTag":"de","rtl":false,"locale":"de_DE","displayName":"Deutsch (German)"},{"languageTag":"in","rtl":false,"locale":"in_ID","displayName":"Bahasa Indonesia (Bahasa Indonesia)"},{"languageTag":"es","rtl":false,"locale":"es_ES","displayName":"Español (Spanish)"},{"languageTag":"tr","rtl":false,"locale":"tr_TR","displayName":"Türkçe (Turkish)"},{"languageTag":"fr","rtl":false,"locale":"fr_FR","displayName":"Français (French)"},{"languageTag":"hi","rtl":false,"locale":"hi_IN","displayName":"हिंदी (Hindi)"},{"languageTag":"it","rtl":false,"locale":"it_IT","displayName":"Italiano (Italian)"},{"languageTag":"ja","rtl":false,"locale":"ja_JP","displayName":"日本語 (Japanese)"},{"languageTag":"nl","rtl":false,"locale":"nl_NL","displayName":"Nederlands (Dutch)"},{"languageTag":"pt","rtl":false,"locale":"pt_BR","displayName":"Português (Portuguese)"},{"languageTag":"sv","rtl":false,"locale":"sv_SE","displayName":"Svenska (Swedish)"},{"languageTag":"pl","rtl":false,"locale":"pl_PL","displayName":"Polski (Polish)"},{"languageTag":"ms","rtl":false,"locale":"ms_MY","displayName":"Bahasa Malaysia (Malay)"},{"languageTag":"ko","rtl":false,"locale":"ko_KR","displayName":"한국어 (Korean)"},{"languageTag":"da","rtl":false,"locale":"da_DK","displayName":"Dansk (Danish)"},{"languageTag":"no","rtl":false,"locale":"no_NO","displayName":"Norsk (Norwegian)"},{"languageTag":"ro","rtl":false,"locale":"ro_RO","displayName":"Română (Romanian)"},{"languageTag":"ru","rtl":false,"locale":"ru_RU","displayName":"Русский (Russian)"},{"languageTag":"zh-hans","rtl":false,"locale":"zh_CN","displayName":"简体中文 (Chinese (Simplified))"},{"languageTag":"zh-hant","rtl":false,"locale":"zh_TW","displayName":"正體中文 (Chinese (Traditional))"},{"languageTag":"th","rtl":false,"locale":"th_TH","displayName":"ภาษาไทย (Thai)"},{"languageTag":"ar","rtl":false,"locale":"ar_AE","displayName":"العربية (Arabic)"}]},"euPhoneNumber":"+44 0-800-085-5752","enableSearchResultsFilterApplyButton":false,"showLanguageSelector":true,"showForumUserHub":false,"showForumHomeLink":true,"forumReadWriteEnabled":false,"hc_product":"linkedin","showHcMachineTranslatedDisclaimer":true,"showGlobalHeaderSearchBar":true,"showPillRecommendedTopics":false,"showSurveyTsx":false,"isBrowsePage":false,"presentationType":"FULL_PAGE","showInternalContent":false,"contactPhoneNumbers":[],"locale":{"code":"en","displayName":"English (English)","dir":"ltr","nameFormat":"first-last"},"chatSupport":null,"chat":{"chatSource":"RNT","chatConfigSF":null,"chatConfigRNT":{"enabled":true,"chatAvailableURL":"https://bcvipac02.rightnowtech.com/Chat/chat/linkedin?action=PROACTIVE_QUERY&responseType=JSON&queue_id=130","chatNowURL":"https://help.linkedin.com/app/chat/init/workflow_id/lcs_help_center_premium","chatWidth":"700","chatHeight":"375","chatAuthWithToken":false},"chatWorkflow":null,"chatPreferredLanguage":"en"},"showProfessionalCommunity":true,"settingsUrl":"https://www.linkedin.com/psettings/?trk=help_settings","isHomePage":true,"hideContactButton":true,"enableForumSemaphore":false,"i18nKeys":{"productNameShort":"LinkedIn","productNameLong":"LinkedIn Help","productHelpForum":"LinkedIn Help Forum"},"showContactSupportOptions":true,"forumEnabled":false,"sessionId":"a4661a03-bc27-4043-8eea-04ce06cd7224|1652212058","uiTheme":"ART_DECO","systemMessage":null,"showFusionLssHomePageExperiment":false,"bodyClass":"has-search-banner","clickToCall":{"clickToCallSource":null,"clickToCallConfigSF":null,"clickToCallConfigRNT":null,"clickToCallWorkflow":null},"showTopLevelBrowse":false,"enablePeopleAlsoView":false,"pageKey":"hc_home","supportedLangs":[{"inHcTag":"en","playLang":{"locale":"en_US","code":"en-US"},"nameFormat":"first-last","hcLocale":"en"},{"inHcTag":"cs","playLang":{"locale":"cs_CZ","code":"cs-CZ"},"nameFormat":"first-last","hcLocale":"cs"},{"inHcTag":"de","playLang":{"locale":"de_DE","code":"de-DE"},"nameFormat":"first-last","hcLocale":"de"},{"inHcTag":"in","playLang":{"locale":"in_ID","code":"id-ID"},"nameFormat":"first-last","hcLocale":"in"},{"inHcTag":"es","playLang":{"locale":"es_ES","code":"es-ES"},"nameFormat":"first-last","hcLocale":"es"},{"inHcTag":"tr","playLang":{"locale":"tr_TR","code":"tr-TR"},"nameFormat":"first-last","hcLocale":"tr"},{"inHcTag":"fr","playLang":{"locale":"fr_FR","code":"fr-FR"},"nameFormat":"first-last","hcLocale":"fr"},{"inHcTag":"hi","playLang":{"locale":"hi_IN","code":"hi-IN"},"nameFormat":"first-last","hcLocale":"hi"},{"inHcTag":"it","playLang":{"locale":"it_IT","code":"it-IT"},"nameFormat":"first-last","hcLocale":"it"},{"inHcTag":"ja","playLang":{"locale":"ja_JP","code":"ja-JP"},"nameFormat":"last-first","hcLocale":"ja"},{"inHcTag":"nl","playLang":{"locale":"nl_NL","code":"nl-NL"},"nameFormat":"first-last","hcLocale":"nl"},{"inHcTag":"pt","playLang":{"locale":"pt_BR","code":"pt-BR"},"nameFormat":"first-last","hcLocale":"pt"},{"inHcTag":"sv","playLang":{"locale":"sv_SE","code":"sv-SE"},"nameFormat":"first-last","hcLocale":"sv"},{"inHcTag":"pl","playLang":{"locale":"pl_PL","code":"pl-PL"},"nameFormat":"first-last","hcLocale":"pl"},{"inHcTag":"ms","playLang":{"locale":"ms_MY","code":"ms-MY"},"nameFormat":"first-last","hcLocale":"ms"},{"inHcTag":"ko","playLang":{"locale":"ko_KR","code":"ko-KR"},"nameFormat":"last-first","hcLocale":"ko"},{"inHcTag":"da","playLang":{"locale":"da_DK","code":"da-DK"},"nameFormat":"first-last","hcLocale":"da"},{"inHcTag":"no","playLang":{"locale":"no_NO","code":"no-NO"},"nameFormat":"first-last","hcLocale":"no"},{"inHcTag":"ro","playLang":{"locale":"ro_RO","code":"ro-RO"},"nameFormat":"first-last","hcLocale":"ro"},{"inHcTag":"ru","playLang":{"locale":"ru_RU","code":"ru-RU"},"nameFormat":"first-last","hcLocale":"ru"},{"inHcTag":"zh-hans","playLang":{"locale":"zh_CN","code":"zh-CN"},"nameFormat":"last-first","hcLocale":"zh__#Hans"},{"inHcTag":"zh-hant","playLang":{"locale":"zh_TW","code":"zh-TW"},"nameFormat":"last-first","hcLocale":"zh__#Hant"},{"inHcTag":"th","playLang":{"locale":"th_TH","code":"th-TH"},"nameFormat":"first-last","hcLocale":"th"},{"inHcTag":"ar","playLang":{"locale":"ar_AE","code":"ar-AE"},"nameFormat":"first-last","hcLocale":"ar"}],"isForumPage":false,"zhHansPhoneNumber":"400-010-6277","copyrightYear":"2022","isVCAODAProdInstanceEnabled":false,"lix":{"helpcenter.play.forum.generateCaseOnAsk":"control","helpcenter.play.forum.generateCaseForAnswer":"control","helpcenter.play.forum.allowCommentsInOrigPost":"control"},"enableGlimmerSearch":false,"forumRightRailRedesign":false,"productLinks":[{"productKey":"linkedin","productNameShort":"LinkedIn"},{"productKey":"sales-navigator","productNameShort":"Sales Navigator"},{"productKey":"billing","productNameShort":"Corporate Billing"},{"productKey":"recruiter","productNameShort":"Recruiter"},{"productKey":"talent-hub","productNameShort":"Talent Hub"},{"productKey":"talent-insights","productNameShort":"Talent Insights"},{"productKey":"lms","productNameShort":"Marketing Solutions"},{"productKey":"sales-insights","productNameShort":"Sales Insights"},{"productKey":"learning","productNameShort":"Learning"}],"notifications":[],"enableDynaformDescriptionValidation":false,"enableAATestingMetricsResearch":false,"usPhoneNumber":"1-844-565-3847","showChat":false,"search":false},"shortcuts":{"shortcutsLinkList":[{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_change_add_email","url":"/psettings/email"}}},{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_reset_password","url":"/uas/request-password-reset?trk=help-feature-launcher"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(50,OSC)","linkText":"Cancel LinkedIn Premium Subscription","id":"50"}}},{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_close_account","url":"/psettings/account-management/close-action-needed"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(83,OSC)","linkText":"LinkedIn Public Profile Visibility","id":"83"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(75815,OSC)","linkText":"Apply for Jobs on LinkedIn","id":"75815"}}}]},"initialPageData":{"path":"/help/linkedin/api/topics","data":{"salesNavigatorPopularActionsVariant":"control","head":{"metadata":{"robots":"index, follow","description":"LinkedIn Help - Need help using LinkedIn? LinkedIn Help is here to help you get answers to your questions.","siteName":"LinkedIn Help","canonicalUrl":"https://www.linkedin.com/help/linkedin?lang=en","title":"LinkedIn Help"}},"popularActionsContact":[],"defaultPopularAction":"EMAIL","pageKey":"hc_home","popularActions":[{"action":"/help/linkedin/answer/71012","name":"Change or add email address"},{"action":"/help/linkedin/answer/69248","name":"Reset your password"},{"action":"/help/linkedin/answer/50","name":"Upgrade or cancel your subscription"},{"action":"/help/linkedin/answer/68889","name":"Close your account"},{"action":"/help/linkedin/answer/71152","name":"Manage emails you get from LinkedIn"},{"action":"/help/linkedin/answer/1275","name":"Merge Connections from Two LinkedIn Accounts"}],"learningPopularActionsVariant":"control"}},"showMobileApps":false,"articlePreviews":[{"id":"67","title":"Manage Emails from LinkedIn","excerpt":"You can manage the types and frequency of emails from LinkedIn and even choose to stop specific emails by unsubscribing. \nTo manage email from your desktop: \n \n Click the  Me icon at the top of your LinkedIn homepage…","articleTopics":[]},{"id":"50","title":"Cancel LinkedIn Premium Subscription","excerpt":"You can only cancel your Premium subscription from the LinkedIn desktop site, mobile browser, or the LinkedIn mobile app, if you bought the Premium subscription via the LinkedIn desktop site. \nTo cancel your Premium…","articleTopics":["Premium","Invoice and Billing Details","Subscription Billing","Basics"]},{"id":"431","title":"Visibility of  Shared Posts","excerpt":"The visibility of posts and engagement activity that appear in the main feed and profile may vary depending on the visibility option that the author has selected for the post. You can't change the visibility option…","articleTopics":[]},{"id":"85598","title":"Visibility and Impact of Your Social Activity on the LinkedIn Feed","excerpt":"Your LinkedIn feed contains professional content from your network, your shares, likes, and posts, companies you follow, and other content that we believe you may be interested in. \nLinkedIn's systems track and…","articleTopics":[]},{"id":"86236","title":"Share Key Profile Updates With Your Network","excerpt":"You can choose to notify your network about important changes made to certain sections of your LinkedIn profile. Enabling notifications about your profile changes may generate a post in your network’s feed, an…","articleTopics":[]},{"id":"123304","title":"Access Country Specific Employment Types","excerpt":"You can now select employment types that are specific to the country in which you’ve worked and more accurately represent your professional experience. \nNote: You must change the location on your introduction section…","articleTopics":[]}],"user":{"headline":"","pictureUrl":"","isLearningAdmin":false,"companies":[],"isSales":false,"email":"","pictureId":"","primaryEmailIsConfirmed":false,"fullName":"","alternativeEmails":[],"accountStatus":"$UNKNOWN","lastName":"","isEnterpriseUser":false,"firstName":"","isRecruiterLiteOnline":false,"isWwe":true,"memberCountry":"","memberId":0,"contractsMetaData":{},"isPremium":false,"isRecruiter":false,"familiarName":"","isGuest":true,"isPaidMember":false},"recommendedTopics":{"topicLinksList":[{"icon":"lightbulb-icon","description":"Basics","id":"a51","title":"Basics"},{"icon":"shield-icon","description":"Data and privacy","id":"a65","title":"Data and Privacy"},{"icon":"money-icon","description":"","id":"104741","title":"Subscription Billing"},{"icon":"person-icon","description":"Your Profile","id":"a64","title":"Your Profile"},{"icon":"connect-icon","description":"2021.05.18 Added for LCS ","id":"a151001","title":"Connections"},{"icon":"briefcase-icon","description":"2021.05.18 Added for LCS ","id":"a153003","title":"Search and Apply for Jobs"}],"allTopicLink":{"id":"127179"}},"showBilling":false}--></code>
        <script>
            fs.embed("templates\/fusion\/pages\/homepage", "templates\/fusion\/pages\/homepage", undefined, undefined);
        </script>
    </section>
    <section class="hc-page__footer">
        <footer class="global-footer">
            <div class="global-footer__upper-row-wrapper">
                <ul class="global-footer__upper-row-items">
                    <li class="global-footer__upper-row-item">
                        <a class="global-footer__upper-row-item-link global-footer__upper-row-item-link--available" href="https://www.linkedin.com">
                            <li-icon class="" type="linkedin-logo" size="14dp" color="brand" tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">LinkedIn</span></a>
                    </li>
                    <li class="global-footer__upper-row-item js-contact-link hidden" data-test-id="footer-contact-us-button"><a class="global-footer__upper-row-item-link global-footer__upper-row-item-link--available" href="/help/linkedin/ask">Contact us</a></li>
                    <li class="global-footer__upper-row-item global-footer__language-switcher-wrapper">
                        <div class="footer-pod language-pod">
                            <div class=" global-footer__language-switcher language-switcher">
                                <form action="" method="GET" class="form js-language-form" aria-label="Select a language"><select name="lang" class="language-switcher__form-select js-language-form-select" data-test-id="language-switcher" aria-label="Select a language" aria-expanded="false"><option value="en" selected>English (English)</option><option value="cs" >Čeština (Czech)</option><option value="de" >Deutsch (German)</option><option value="in" >Bahasa Indonesia (Bahasa Indonesia)</option><option value="es" >Español (Spanish)</option><option value="tr" >Türkçe (Turkish)</option><option value="fr" >Français (French)</option><option value="hi" >हिंदी (Hindi)</option><option value="it" >Italiano (Italian)</option><option value="ja" >日本語 (Japanese)</option><option value="nl" >Nederlands (Dutch)</option><option value="pt" >Português (Portuguese)</option><option value="sv" >Svenska (Swedish)</option><option value="pl" >Polski (Polish)</option><option value="ms" >Bahasa Malaysia (Malay)</option><option value="ko" >한국어 (Korean)</option><option value="da" >Dansk (Danish)</option><option value="no" >Norsk (Norwegian)</option><option value="ro" >Română (Romanian)</option><option value="ru" >Русский (Russian)</option><option value="zh-hans" >简体中文 (Chinese (Simplified))</option><option value="zh-hant" >正體中文 (Chinese (Traditional))</option><option value="th" >ภาษาไทย (Thai)</option><option value="ar" >العربية (Arabic)</option></select></form>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
            <div class="global-footer__lower-row-wrapper">
                <ul class="global-footer__lower-row-items">
                    <li class="global-footer__lower-row-item"><a class="global-footer__lower-row-item-link" data-test-id="footer-about" target="_blank" href="//linkedin.com/about-us">About</a></li>
                    <li class="global-footer__lower-row-item"><a class="global-footer__lower-row-item-link" target="_blank" href="//safety.linkedin.com">Safety Center</a></li>
                    <li class=" global-footer__lower-row-item privacy-dropdown dropdown__container"><button class="privacy-dropdown__button dropdown__trigger plain-button" aria-expanded="false" aria-controls="privacy-dropdown__menu">Privacy and Terms<li-icon class="privacy-dropdown__caret-icon" type="caret-filled-down-icon" size="small" color="" tabindex="-1" aria-hidden="true"></li-icon></button>
                        <div
                            id="privacy-dropdown__menu" class="privacy-dropdown__menu dropdown__menu dropdown__menu--up dropdown__menu--inverse" tabindex="-1" aria-hidden="true"><a class="privacy-dropdown__link dropdown__menu-item" target="_blank" href="//linkedin.com/legal/cookie-policy">Cookies</a><a class="privacy-dropdown__link dropdown__menu-item" target="_blank" href="//linkedin.com/legal/copyright-policy">Copyright</a>
                            <a
                                class="privacy-dropdown__link dropdown__menu-item" target="_blank" href="//linkedin.com/legal/user-agreement">Terms</a><a class="privacy-dropdown__link dropdown__menu-item" target="_blank" href="//linkedin.com/legal/privacy-policy">Privacy</a><a class="privacy-dropdown__link dropdown__menu-item" target="_blank" href="//linkedin.com/psettings/guest-controls">Guest controls</a></div>
            </li>
            <li class="global-footer__lower-row-item global-footer__lower-row-item--first"><span class="linkedin-copy mobile-copyright">LinkedIn Corporation &copy; 2022</span></li>
            </ul>
            </div>
            <div class="survey is-not-started mobile-excluded js-survey" data-test-id="survey-container">
                <div class="survey-questions js-survey-questions">
                    <header class="survey-prompt" data-test-id="survey-prompt"><button class="survey-prompt__title survey-trigger js-survey-trigger plain-button" data-test-selector="survey-trigger"><span aria-hidden="true">We’d like your feedback</span><span class="visually-hidden">You are on the feedback overlay. Press enter to open the survey.</span></button>
                        <button
                            class="survey-prompt__button survey-prompt__button--collapsed survey-trigger js-survey-trigger artdeco-button artdeco-button--1 artdeco-button--circle artdeco-button--tertiary artdeco-button--muted" data-component-id="survey-prompt-button-toggle"
                            data-test-selector="survey-trigger">
                            <li-icon class="svg-icon " type="chevron-up-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden" data-component-id="survey-trigger-a11y-text">You are on the feedback overlay. Press enter to open the survey.</span></button><button class="survey-prompt__button survey-prompt__button--dismiss survey-dismiss js-survey-dismiss artdeco-button artdeco-button--1 artdeco-button--circle artdeco-button--tertiary artdeco-button--muted"
                                data-test-id="survey-dismiss"><li-icon class="svg-icon " type="cancel-icon" size="large" color=""  tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">dismiss this message</span></button></header>
                    <div class="survey-form-container js-survey-form-container"
                        aria-hidden="true">
                        <form class="survey-form js-survey-form" method="post" name="_main">
                            <div class="question-container js-question-container">
                                <fieldset class="field current" tabindex="-1">
                                    <legend class="survey-question"><span id="q948">Overall, how satisfied were you with your experience on the LinkedIn Help Center today?</span><span class="required-indicator"> <span title='required' aria-hidden="true">*</span> <span class="a11y-hidden">This field is required.</span></span>
                                    </legend>
                                    <ul class="option-container">
                                        <li><input name="q_948" type="radio" value="4099" id="q_948_4099" /><label for="q_948_4099" data-test-selector="selected-answer-one">Very satisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4100" id="q_948_4100" /><label for="q_948_4100">Satisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4101" id="q_948_4101" /><label for="q_948_4101">Somewhat satisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4102" id="q_948_4102" /><label for="q_948_4102">Neither satisfied nor dissatisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4103" id="q_948_4103" /><label for="q_948_4103">Somewhat dissatisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4104" id="q_948_4104" /><label for="q_948_4104">Dissatisfied</label></li>
                                        <li><input name="q_948" type="radio" value="4105" id="q_948_4105" /><label for="q_948_4105">Very dissatisfied</label></li>
                                    </ul>
                                </fieldset>
                                <fieldset class="field js-field" tabindex="-1">
                                    <legend class="survey-question"><span id="q947">What was your primary purpose for visiting the LinkedIn Help Center today?</span><span class="required-indicator"> <span title='required' aria-hidden="true">*</span> <span class="a11y-hidden">This field is required.</span></span>
                                    </legend>
                                    <ul class="option-container">
                                        <li><input name="q_947" type="radio" value="4091" id="q_947_4091" /><label for="q_947_4091" data-test-selector="selected-answer-two">I wanted to learn the basics</label></li>
                                        <li><input name="q_947" type="radio" value="4092" id="q_947_4092" /><label for="q_947_4092">I know the basics, but wanted to learn more</label></li>
                                        <li><input name="q_947" type="radio" value="4093" id="q_947_4093" /><label for="q_947_4093">I came to find out how to fix a problem on my own</label></li>
                                        <li><input name="q_947" type="radio" value="4094" id="q_947_4094" /><label for="q_947_4094">I came to contact customer support</label></li>
                                        <li><input name="q_947" type="radio" value="4095" id="q_947_4095" /><label for="q_947_4095">I came to follow up on a previous support ticket</label></li>
                                        <li><input name="q_947" type="radio" value="4096" id="q_947_4096" /><label for="q_947_4096">I wanted to participate in the community forum</label></li>
                                        <li><input name="q_947" type="radio" value="4097" id="q_947_4097" /><label for="q_947_4097">I had another purpose for my visit</label></p>
                                    </ul>
                                </fieldset>
                                <fieldset class="field js-field" tabindex="-1">
                                    <legend class="survey-question"><span id="q945">Were you able to complete your intended purpose today?</span><span class="required-indicator"> <span title='required' aria-hidden="true">*</span> <span class="a11y-hidden">This field is required.</span></span>
                                    </legend>
                                    <ul class="option-container">
                                        <li><input name="q_945" type="radio" value="4089" id="q_945_4089" /><label for="q_945_4089" data-test-selector="selected-answer-three">Yes</label></li>
                                        <li><input name="q_945" type="radio" value="4090" id="q_945_4090" /><label for="q_945_4090">No</label></li>
                                        <li><input name="q_945" type="radio" value="4098" id="q_945_4098" /><label for="q_945_4098">Uncertain</label></p>
                                    </ul>
                                </fieldset>
                            </div>
                            <div class="controls-container">
                                <div class="survey-progress js-survey-progress" aria-hidden="true" data-test-id="survey-progress">Question 1 of 3</div>
                                <div class="survey-buttons"><button disabled id="submit_btn" type="submit" class="btn btn-primary hidden js-survey-submit" data-test-id="survey-submit">Submit</button>
                                    <div class="survey-pagination js-survey-pagination"><button disabled type="button" class="btn btn-next btn-primary js-btn js-btn-next" data-test-id="survey-next">Next</button></div>
                                </div><span class="js-survey-reset a11y-hidden" tabindex="0"></span><span class="js-survey-previous a11y-hidden" tabindex="0"></span></div>
                        </form>
                    </div>
                </div>
                <div class="survey-complete hidden js-survey-complete" data-test-id="survey-complete-container" tabindex="-1">
                    <div class="survey-complete-message">
                        <div class="icon-wrapper" data-test-id="survey-complete-icon">
                            <li-icon class="svg-icon " type="check-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon>
                        </div>
                        <h2 class="survey-complete-message-header" data-test-id="survey-complete-header">Thank you</h2>
                        <p class="survey-complete-message-copy" data-test-id="survey-complete-description">We’ll use your feedback to improve the experience.</p><button class="survey-close js-survey-dismiss artdeco-button artdeco-button--2 artdeco-button--primary" data-test-id="survey-complete-close-button">Close</button></div>
                    <button
                        class="survey-dismiss js-survey-dismiss artdeco-button artdeco-button--1 artdeco-button--circle artdeco-button--tertiary artdeco-button--muted" data-test-id="survey-complete-dismiss-button">
                        <li-icon class="svg-icon " type="cancel-icon" size="large" color="" tabindex="-1" aria-hidden="true"></li-icon><span class="visually-hidden">dismiss this message</span></button>
                </div>
            </div>
        </footer>
    </section>
    <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/eocusep60b16wcsp1yjil9spn"></script>
    <script src='https://static-exp1.licdn.com/sc/h/8hfbuq1ftcvnnx4dd5067pi0t' async></script>
    <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/8x5xlelf2jf147zwb5mhxmacr"></script>
    <code id="client-template" style="display: none;"><!--"templates/fusion/pages/homepage"--></code><code id="client-data" style="display: none;"><!--{"head":{},"pageData":{"pageAside":{"ticketSupport":{"descriptionI18nKey":"i18n_common_contact_support_ticket_message_support","illustration":"mail-closed","ctaI18nKey":"i18n_common_contact_support_ticket_create_link_text","headerI18nKey":"i18n_common_contact_support_ticket_create"},"professionalCommunity":{"descriptionI18nKey":"i18n_common_our_policies_ensure","illustration":"people-conversation","ctaI18nKey":"i18n_common_learn_more","headerI18nKey":"i18n_common_professional_community_policies"},"showContactUs":true,"safetyCenter":{"descriptionI18nKey":"i18n_common_your_account_security","illustration":"lock","ctaI18nKey":"i18n_common_learn_more","headerI18nKey":"i18n_common_safety_center"},"clickToCallSupport":{"offlineIllustration":"mobile-phone-muted","onlineDescriptionI18nKey":"i18n_common_contact_support_click_to_call_online","onlineIllustration":"mobile-phone","onlineCtaI18nKey":"i18n_landing_page_contact_support_option_phone_link_text_available","inProgressDescriptionI18nKey":"i18n_common_contact_support_click_to_call_in_progress","offlineHeaderI18nKey":"i18n_popular_actions_request_phone_call_available","onlineHeaderI18nKey":"i18n_popular_actions_request_phone_call_available","offlineDescriptionI18nKey":"i18n_popular_actions_contact_option_unavailable"}}},"global":{"referralUrl":"","showClickToCall":false,"nativeConfig":{"nativeHomeId":5069,"nativeHideSearch":false,"nativeHideContact":false,"nativeHideHomeLink":false},"productParams":{"productName":"linkedin","appChooserIcon":"app-linkedin-bug-color-icon","productIcon":"linkedin","productUrl":"https://www.linkedin.com/","productType":"website"},"showChatCtcLlsUnbound":false,"isDynamicsCaseEnabled":true,"path":"/help/linkedin","showForumDriver":false,"showSafetyCenter":true,"showFusionLssCommunityLink":false,"showSurvey":true,"languageSwitcher":{"supportedLanguages":[{"languageTag":"en","rtl":false,"locale":"en_US","displayName":"English (English)"},{"languageTag":"cs","rtl":false,"locale":"cs_CZ","displayName":"Čeština (Czech)"},{"languageTag":"de","rtl":false,"locale":"de_DE","displayName":"Deutsch (German)"},{"languageTag":"in","rtl":false,"locale":"in_ID","displayName":"Bahasa Indonesia (Bahasa Indonesia)"},{"languageTag":"es","rtl":false,"locale":"es_ES","displayName":"Español (Spanish)"},{"languageTag":"tr","rtl":false,"locale":"tr_TR","displayName":"Türkçe (Turkish)"},{"languageTag":"fr","rtl":false,"locale":"fr_FR","displayName":"Français (French)"},{"languageTag":"hi","rtl":false,"locale":"hi_IN","displayName":"हिंदी (Hindi)"},{"languageTag":"it","rtl":false,"locale":"it_IT","displayName":"Italiano (Italian)"},{"languageTag":"ja","rtl":false,"locale":"ja_JP","displayName":"日本語 (Japanese)"},{"languageTag":"nl","rtl":false,"locale":"nl_NL","displayName":"Nederlands (Dutch)"},{"languageTag":"pt","rtl":false,"locale":"pt_BR","displayName":"Português (Portuguese)"},{"languageTag":"sv","rtl":false,"locale":"sv_SE","displayName":"Svenska (Swedish)"},{"languageTag":"pl","rtl":false,"locale":"pl_PL","displayName":"Polski (Polish)"},{"languageTag":"ms","rtl":false,"locale":"ms_MY","displayName":"Bahasa Malaysia (Malay)"},{"languageTag":"ko","rtl":false,"locale":"ko_KR","displayName":"한국어 (Korean)"},{"languageTag":"da","rtl":false,"locale":"da_DK","displayName":"Dansk (Danish)"},{"languageTag":"no","rtl":false,"locale":"no_NO","displayName":"Norsk (Norwegian)"},{"languageTag":"ro","rtl":false,"locale":"ro_RO","displayName":"Română (Romanian)"},{"languageTag":"ru","rtl":false,"locale":"ru_RU","displayName":"Русский (Russian)"},{"languageTag":"zh-hans","rtl":false,"locale":"zh_CN","displayName":"简体中文 (Chinese (Simplified))"},{"languageTag":"zh-hant","rtl":false,"locale":"zh_TW","displayName":"正體中文 (Chinese (Traditional))"},{"languageTag":"th","rtl":false,"locale":"th_TH","displayName":"ภาษาไทย (Thai)"},{"languageTag":"ar","rtl":false,"locale":"ar_AE","displayName":"العربية (Arabic)"}]},"euPhoneNumber":"+44 0-800-085-5752","enableSearchResultsFilterApplyButton":false,"showLanguageSelector":true,"showForumUserHub":false,"showForumHomeLink":true,"forumReadWriteEnabled":false,"hc_product":"linkedin","showHcMachineTranslatedDisclaimer":true,"showGlobalHeaderSearchBar":true,"showPillRecommendedTopics":false,"showSurveyTsx":false,"isBrowsePage":false,"presentationType":"FULL_PAGE","showInternalContent":false,"contactPhoneNumbers":[],"locale":{"code":"en","displayName":"English (English)","dir":"ltr","nameFormat":"first-last"},"chatSupport":null,"chat":{"chatSource":"RNT","chatConfigSF":null,"chatConfigRNT":{"enabled":true,"chatAvailableURL":"https://bcvipac02.rightnowtech.com/Chat/chat/linkedin?action=PROACTIVE_QUERY&responseType=JSON&queue_id=130","chatNowURL":"https://help.linkedin.com/app/chat/init/workflow_id/lcs_help_center_premium","chatWidth":"700","chatHeight":"375","chatAuthWithToken":false},"chatWorkflow":null,"chatPreferredLanguage":"en"},"showProfessionalCommunity":true,"settingsUrl":"https://www.linkedin.com/psettings/?trk=help_settings","isHomePage":true,"hideContactButton":true,"enableForumSemaphore":false,"i18nKeys":{"productNameShort":"LinkedIn","productNameLong":"LinkedIn Help","productHelpForum":"LinkedIn Help Forum"},"showContactSupportOptions":true,"forumEnabled":false,"sessionId":"a4661a03-bc27-4043-8eea-04ce06cd7224|1652212058","uiTheme":"ART_DECO","systemMessage":null,"showFusionLssHomePageExperiment":false,"bodyClass":"has-search-banner","clickToCall":{"clickToCallSource":null,"clickToCallConfigSF":null,"clickToCallConfigRNT":null,"clickToCallWorkflow":null},"showTopLevelBrowse":false,"enablePeopleAlsoView":false,"pageKey":"hc_home","supportedLangs":[{"inHcTag":"en","playLang":{"locale":"en_US","code":"en-US"},"nameFormat":"first-last","hcLocale":"en"},{"inHcTag":"cs","playLang":{"locale":"cs_CZ","code":"cs-CZ"},"nameFormat":"first-last","hcLocale":"cs"},{"inHcTag":"de","playLang":{"locale":"de_DE","code":"de-DE"},"nameFormat":"first-last","hcLocale":"de"},{"inHcTag":"in","playLang":{"locale":"in_ID","code":"id-ID"},"nameFormat":"first-last","hcLocale":"in"},{"inHcTag":"es","playLang":{"locale":"es_ES","code":"es-ES"},"nameFormat":"first-last","hcLocale":"es"},{"inHcTag":"tr","playLang":{"locale":"tr_TR","code":"tr-TR"},"nameFormat":"first-last","hcLocale":"tr"},{"inHcTag":"fr","playLang":{"locale":"fr_FR","code":"fr-FR"},"nameFormat":"first-last","hcLocale":"fr"},{"inHcTag":"hi","playLang":{"locale":"hi_IN","code":"hi-IN"},"nameFormat":"first-last","hcLocale":"hi"},{"inHcTag":"it","playLang":{"locale":"it_IT","code":"it-IT"},"nameFormat":"first-last","hcLocale":"it"},{"inHcTag":"ja","playLang":{"locale":"ja_JP","code":"ja-JP"},"nameFormat":"last-first","hcLocale":"ja"},{"inHcTag":"nl","playLang":{"locale":"nl_NL","code":"nl-NL"},"nameFormat":"first-last","hcLocale":"nl"},{"inHcTag":"pt","playLang":{"locale":"pt_BR","code":"pt-BR"},"nameFormat":"first-last","hcLocale":"pt"},{"inHcTag":"sv","playLang":{"locale":"sv_SE","code":"sv-SE"},"nameFormat":"first-last","hcLocale":"sv"},{"inHcTag":"pl","playLang":{"locale":"pl_PL","code":"pl-PL"},"nameFormat":"first-last","hcLocale":"pl"},{"inHcTag":"ms","playLang":{"locale":"ms_MY","code":"ms-MY"},"nameFormat":"first-last","hcLocale":"ms"},{"inHcTag":"ko","playLang":{"locale":"ko_KR","code":"ko-KR"},"nameFormat":"last-first","hcLocale":"ko"},{"inHcTag":"da","playLang":{"locale":"da_DK","code":"da-DK"},"nameFormat":"first-last","hcLocale":"da"},{"inHcTag":"no","playLang":{"locale":"no_NO","code":"no-NO"},"nameFormat":"first-last","hcLocale":"no"},{"inHcTag":"ro","playLang":{"locale":"ro_RO","code":"ro-RO"},"nameFormat":"first-last","hcLocale":"ro"},{"inHcTag":"ru","playLang":{"locale":"ru_RU","code":"ru-RU"},"nameFormat":"first-last","hcLocale":"ru"},{"inHcTag":"zh-hans","playLang":{"locale":"zh_CN","code":"zh-CN"},"nameFormat":"last-first","hcLocale":"zh__#Hans"},{"inHcTag":"zh-hant","playLang":{"locale":"zh_TW","code":"zh-TW"},"nameFormat":"last-first","hcLocale":"zh__#Hant"},{"inHcTag":"th","playLang":{"locale":"th_TH","code":"th-TH"},"nameFormat":"first-last","hcLocale":"th"},{"inHcTag":"ar","playLang":{"locale":"ar_AE","code":"ar-AE"},"nameFormat":"first-last","hcLocale":"ar"}],"isForumPage":false,"zhHansPhoneNumber":"400-010-6277","copyrightYear":"2022","isVCAODAProdInstanceEnabled":false,"lix":{"helpcenter.play.forum.generateCaseOnAsk":"control","helpcenter.play.forum.generateCaseForAnswer":"control","helpcenter.play.forum.allowCommentsInOrigPost":"control"},"enableGlimmerSearch":false,"forumRightRailRedesign":false,"productLinks":[{"productKey":"linkedin","productNameShort":"LinkedIn"},{"productKey":"sales-navigator","productNameShort":"Sales Navigator"},{"productKey":"billing","productNameShort":"Corporate Billing"},{"productKey":"recruiter","productNameShort":"Recruiter"},{"productKey":"talent-hub","productNameShort":"Talent Hub"},{"productKey":"talent-insights","productNameShort":"Talent Insights"},{"productKey":"lms","productNameShort":"Marketing Solutions"},{"productKey":"sales-insights","productNameShort":"Sales Insights"},{"productKey":"learning","productNameShort":"Learning"}],"notifications":[],"enableDynaformDescriptionValidation":false,"enableAATestingMetricsResearch":false,"usPhoneNumber":"1-844-565-3847","showChat":false,"search":false},"shortcuts":{"shortcutsLinkList":[{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_change_add_email","url":"/psettings/email"}}},{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_reset_password","url":"/uas/request-password-reset?trk=help-feature-launcher"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(50,OSC)","linkText":"Cancel LinkedIn Premium Subscription","id":"50"}}},{"link":{"externalLink":{"i18nLinkKey":"i18n_consumer_shortcut_close_account","url":"/psettings/account-management/close-action-needed"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(83,OSC)","linkText":"LinkedIn Public Profile Visibility","id":"83"}}},{"link":{"articleLink":{"urn":"urn:li:helpCenterArticle:(75815,OSC)","linkText":"Apply for Jobs on LinkedIn","id":"75815"}}}]},"initialPageData":{"path":"/help/linkedin/api/topics","data":{"salesNavigatorPopularActionsVariant":"control","head":{"metadata":{"robots":"index, follow","description":"LinkedIn Help - Need help using LinkedIn? LinkedIn Help is here to help you get answers to your questions.","siteName":"LinkedIn Help","canonicalUrl":"https://www.linkedin.com/help/linkedin?lang=en","title":"LinkedIn Help"}},"popularActionsContact":[],"defaultPopularAction":"EMAIL","pageKey":"hc_home","popularActions":[{"action":"/help/linkedin/answer/71012","name":"Change or add email address"},{"action":"/help/linkedin/answer/69248","name":"Reset your password"},{"action":"/help/linkedin/answer/50","name":"Upgrade or cancel your subscription"},{"action":"/help/linkedin/answer/68889","name":"Close your account"},{"action":"/help/linkedin/answer/71152","name":"Manage emails you get from LinkedIn"},{"action":"/help/linkedin/answer/1275","name":"Merge Connections from Two LinkedIn Accounts"}],"learningPopularActionsVariant":"control"}},"showMobileApps":false,"articlePreviews":[{"id":"67","title":"Manage Emails from LinkedIn","excerpt":"You can manage the types and frequency of emails from LinkedIn and even choose to stop specific emails by unsubscribing. \nTo manage email from your desktop: \n \n Click the  Me icon at the top of your LinkedIn homepage…","articleTopics":[]},{"id":"50","title":"Cancel LinkedIn Premium Subscription","excerpt":"You can only cancel your Premium subscription from the LinkedIn desktop site, mobile browser, or the LinkedIn mobile app, if you bought the Premium subscription via the LinkedIn desktop site. \nTo cancel your Premium…","articleTopics":["Premium","Invoice and Billing Details","Subscription Billing","Basics"]},{"id":"431","title":"Visibility of  Shared Posts","excerpt":"The visibility of posts and engagement activity that appear in the main feed and profile may vary depending on the visibility option that the author has selected for the post. You can't change the visibility option…","articleTopics":[]},{"id":"85598","title":"Visibility and Impact of Your Social Activity on the LinkedIn Feed","excerpt":"Your LinkedIn feed contains professional content from your network, your shares, likes, and posts, companies you follow, and other content that we believe you may be interested in. \nLinkedIn's systems track and…","articleTopics":[]},{"id":"86236","title":"Share Key Profile Updates With Your Network","excerpt":"You can choose to notify your network about important changes made to certain sections of your LinkedIn profile. Enabling notifications about your profile changes may generate a post in your network’s feed, an…","articleTopics":[]},{"id":"123304","title":"Access Country Specific Employment Types","excerpt":"You can now select employment types that are specific to the country in which you’ve worked and more accurately represent your professional experience. \nNote: You must change the location on your introduction section…","articleTopics":[]}],"user":{"headline":"","pictureUrl":"","isLearningAdmin":false,"companies":[],"isSales":false,"email":"","pictureId":"","primaryEmailIsConfirmed":false,"fullName":"","alternativeEmails":[],"accountStatus":"$UNKNOWN","lastName":"","isEnterpriseUser":false,"firstName":"","isRecruiterLiteOnline":false,"isWwe":true,"memberCountry":"","memberId":0,"contractsMetaData":{},"isPremium":false,"isRecruiter":false,"familiarName":"","isGuest":true,"isPaidMember":false},"recommendedTopics":{"topicLinksList":[{"icon":"lightbulb-icon","description":"Basics","id":"a51","title":"Basics"},{"icon":"shield-icon","description":"Data and privacy","id":"a65","title":"Data and Privacy"},{"icon":"money-icon","description":"","id":"104741","title":"Subscription Billing"},{"icon":"person-icon","description":"Your Profile","id":"a64","title":"Your Profile"},{"icon":"connect-icon","description":"2021.05.18 Added for LCS ","id":"a151001","title":"Connections"},{"icon":"briefcase-icon","description":"2021.05.18 Added for LCS ","id":"a153003","title":"Search and Apply for Jobs"}],"allTopicLink":{"id":"127179"}},"showBilling":false}--></code>
    <script
        type="text/javascript" src="https://static-exp1.licdn.com/sc/h/76klx2dpwcrpu3ub0x7wwvouv"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/8x5xlelf2jf147zwb5mhxmacr"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/1j8qy5boy0ls2neb33y3fyjrq"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/5nbydn06shs9yp06rbqsdlh3c"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/6bj4olfpx6gy4j3p9f731cjgr"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/7f44tfob7u225jfu0ax24xtfw"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/1zmb3fz1be1e4duy248wtmar5"></script>
        <script type="text/javascript" src="https://static-exp1.licdn.com/sc/h/8h3j7vhfgstl4q3bifzoi0npc"></script>
        </div>
        </div>
</body>

</html>
