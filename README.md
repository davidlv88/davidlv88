

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Home</title>
    <meta name="viewport" content="width=device-width, initial-scale=0.7, user-scalable=yes">
    <link rel="shortcut icon" type="image/x-icon" href="/site-main/favico.ico" />
    <link href="https://stcdn.b8ag.com/bundles/common/common.min.css?v=20240124" rel="stylesheet" type="text/css">
    <link href="https://stcdn.b8ag.com/bundles/site-main/master.min.css?v=1.0.8824.16260.20231219" rel="stylesheet" type="text/css">
    <link href="/site-main/assets/bundles/default-index.min.css?v=1.0.8824.16260.20231219" rel="stylesheet" type="text/css">
    <link href="/site-main/assets/bundles/page-mobile-calculate-07.min.css?v=1.0.8824.16260.20231219" rel="stylesheet" type="text/css" media="screen and (max-device-width: 767px)">
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://stcdn.b8ag.com/bundles/common/support-IE8.min.js?v=20240124" type="text/javascript"></script>
    <![endif]-->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
                                    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
                                    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
                                    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
                                    })(window,document,'script','dataLayer','GTM-KSQNFQP');</script>
</head>
<body>
    <noscript><iframe src='https://www.googletagmanager.com/ns.html?id=GTM-KSQNFQP' height='0' width='0' style='display:none;visibility:hidden'></iframe></noscript>
    <div id="page-popup" class="modal fade hidden" role="dialog" aria-labelledby="myModalLabel">
    <div class="modal-dialog ex-modal" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"></span></button>
                <h4 class="modal-title" id="result-detail-title"><span class="popup-title" id="popup-title"></span></h4>
            </div>
            <div class="modal-body">
                <iframe frameborder="0" allowtransparency="true" marginheight="0" marginwidth="0" scrolling="auto"
                        id="popup-iframe"></iframe>
            </div>
        </div>
    </div>
</div>

    <div class="modal fade message-modal" id="userMessageModal" role="dialog" aria-labelledby="myModalLabel">
    <div class="modal-dialog modal-sm" role="document">
        <div class="modal-content">
            <div class="modal-body" id="userMessageModalBody">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"></span></button>
                <div id="msg-content">                    
                </div>
                <a class="link hide showmore-container">More</a>
                <a class="link hide showless-container">less</a>
            </div>
        </div>
    </div>
</div>
    <aside class="sidebar" id="side-bar">
        <div class="partial-content customer-profile" id="profile" data-url="/site-main/CustomerProfile/BriefProfile"></div>
        <nav class="navigation" id="navigation">
            <ul class="main-tab">
    <li id="main-menu-header" class="mainmenu active withripple" data-target-container="mainmenu-container">
        <a>Main menu</a>
    </li>
        <li class="accountinfo withripple" id="account-info-header"
            data-target-container="accountinfo-container">
            <a>Account Info</a>
        </li>
    <li class="visible-mobile nav-close">
        <span class='icon-close icon-close-left-panel' id="closeIconOnMobile"></span>
    </li>
</ul>
<section id="main-menu-tab" class="mainmenu-container mCustomScrollbar " data-mcs-theme="minimal-dark" role="tablist" aria-multiselectable="true">
    <ul class="list-menu" id="main-menu-items">
                <li class="menu-item " id="menu-REPORTS">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-reports">
                            <span class="icon icon-reports"></span>
                            Reports
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="/site-reports" data-url="/site-reports/outstanding/agentnew" class="sub-menu-item " id="sub-menu-AGENTOUTSTANDING">
                                <a href="#" class="redirect-item">
                                    Agent Outstanding
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/enteredresult/agent" class="sub-menu-item " id="sub-menu-AGENTWINLOSS">
                                <a href="#" class="redirect-item">
                                    Agent Win Loss
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/winlossdetail/agentnew" class="sub-menu-item " id="sub-menu-AGENTWINLOSTDETAIL">
                                <a href="#" class="redirect-item">
                                    Agent Win Loss Detail
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/matchwinlossdetail/index" class="sub-menu-item " id="sub-menu-MATCHWINLOSTDETAIL">
                                <a href="#" class="redirect-item">
                                    Match Win Loss Detail
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/winlossanalysis/agent" class="sub-menu-item " id="sub-menu-WINLOSSANALYSIS">
                                <a href="#" class="redirect-item">
                                    Win Loss Analysis
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/winlossanalysischart/agent" class="sub-menu-item " id="sub-menu-WINLOSSANALYSISCHART">
                                <a href="#" class="redirect-item">
                                    Win Loss Analysis Chart
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/WinLossByProduct/agent" class="sub-menu-item " id="sub-menu-WINLOSSBYPRODUCT">
                                <a href="#" class="redirect-item">
                                    Win Loss By Product
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/commissionbybettype/agent" class="sub-menu-item " id="sub-menu-COMMISSIONBYBETTYPE">
                                <a href="#" class="redirect-item">
                                    Commission By Bet Type
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/Statement/SMAStatement" class="sub-menu-item " id="sub-menu-STATEMENT">
                                <a href="#" class="redirect-item">
                                    Statement
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-results/Normal" class="sub-menu-item " id="sub-menu-RESULT">
                                <a href="#" class="redirect-item">
                                    Results
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/progressivecontribution/index" class="sub-menu-item " id="sub-menu-PROGRESSIVEGAMESCONTRIBUTION">
                                <a href="#" class="redirect-item">
                                    Progressive Games Contribution
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-reports" data-url="/site-reports/betcredithistory/index" class="sub-menu-item " id="sub-menu-BETCREDITTRACKING">
                                <a href="#" class="redirect-item">
                                    Bet Credit Tracking
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item " id="menu-MEMBERINFO">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-memberinfo">
                            <span class="icon icon-memberinfo"></span>
                            MEMBER INFORMATION
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="" data-url="/site-memberinfo/CopyAccount?lv=3" class="sub-menu-item " id="sub-menu-NEWAGENT">
                                <a href="#" class="redirect-item">
                                    New Agent
                                    
                                    <span class="beta-version">New</span>
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/PTTemplate/Index?lng=en-US&amp;isDarkMode=false" class="sub-menu-item " id="sub-menu-PTTEMPLATE">
                                <a href="#" class="redirect-item">
                                    Position Taking Template
                                    
                                    <span class="beta-version">New</span>
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/CustomerList/agent" class="sub-menu-item " id="sub-menu-AGENTLIST">
                                <a href="#" class="redirect-item">
                                    Agent List
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/ProblemAccount" class="sub-menu-item " id="sub-menu-PROBLEMACCOUNTLIST">
                                <a href="#" class="redirect-item">
                                    Problem Account List
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/CreditBalance" class="sub-menu-item " id="sub-menu-CREDITBALANCE">
                                <a href="#" class="redirect-item">
                                    Credit/Balance
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-main/_MemberInfo/PositionTakingList/Sportbook/SportbookPositionTakingList.aspx" class="sub-menu-item " id="sub-menu-POSITIONTAKING">
                                <a href="#" class="redirect-item">
                                    Position Taking (%)
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-main/_MemberInfo/Commission/MemberCommissionSportbook.aspx" class="sub-menu-item " id="sub-menu-MEMBERCOMMISSION">
                                <a href="#" class="redirect-item">
                                    Member Commission
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/IndirectLoginAccount/Index" class="sub-menu-item " id="sub-menu-INDIRECTLOGINACCOUNT">
                                <a href="#" class="redirect-item">
                                    Indirect Login Account
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/DormantAccount/Index" class="sub-menu-item " id="sub-menu-DORMANTACCOUNTLIST">
                                <a href="#" class="redirect-item">
                                    Dormant Account List
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item " id="menu-BETLISTS">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-betlists">
                            <span class="icon icon-betlists"></span>
                            Bet Lists
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="/site-betlists" data-url="/site-betlists/SearchTickets/Index" class="sub-menu-item " id="sub-menu-SEARCHTICKETS">
                                <a href="#" class="redirect-item">
                                    Search Tickets
                                    
                                    <span class="beta-version">New</span>
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/CancelledBet/Index" class="sub-menu-item " id="sub-menu-CANCELLEDBETS">
                                <a href="#" class="redirect-item">
                                    Cancelled Bets
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/correctscore/index" class="sub-menu-item " id="sub-menu-CORRECTSCORE">
                                <a href="#" class="redirect-item">
                                    Correct Score
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/CombinationMixParlay/Index" class="sub-menu-item " id="sub-menu-PARLAY">
                                <a href="#" class="redirect-item">
                                    Parlay
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/betlistbybettype/CleanSheet?bettype=13" class="sub-menu-item " id="sub-menu-BETTYPE13">
                                <a href="#" class="redirect-item">
                                    Clean Sheet
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/betlistbybettype/DoubleChance?bettype=24" class="sub-menu-item " id="sub-menu-BETTYPE24">
                                <a href="#" class="redirect-item">
                                    Double Chance
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/betlistbybettype/BothNoneNeitherTeamToScore?bettype=26" class="sub-menu-item " id="sub-menu-BETTYPE26">
                                <a href="#" class="redirect-item">
                                    Both/One/Neither Team To Score
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/betlistbybettype/ToWinToNil?bettype=27" class="sub-menu-item " id="sub-menu-BETTYPE27">
                                <a href="#" class="redirect-item">
                                    To Win To Nil
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="/site-betlists" data-url="/site-betlists/betlistbybettype/ThreeWayHandicap?bettype=28" class="sub-menu-item " id="sub-menu-BETTYPE28">
                                <a href="#" class="redirect-item">
                                    3-Way Handicap
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item " id="menu-BETSANDFORECAST">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-betsandforecast">
                            <span class="icon icon-betsandforecast"></span>
                            Bets & Forecast
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="" data-url="/site-totalbetsforecast/Forecast" class="sub-menu-item " id="sub-menu-SOCCER">
                                <a href="#" class="redirect-item">
                                    Soccer
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/HDPOU.aspx" class="sub-menu-item " id="sub-menu-HOUL">
                                <a href="#" class="redirect-item">
                                    Handicap/Over Under/Live
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/MoneyLine.aspx" class="sub-menu-item " id="sub-menu-MONEYLINE">
                                <a href="#" class="redirect-item">
                                    Money Line
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/OddEven1x2.aspx" class="sub-menu-item " id="sub-menu-OE1X2DND">
                                <a href="#" class="redirect-item">
                                    Odd/Even + 1x2 + DND
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/TotalGoal.aspx" class="sub-menu-item " id="sub-menu-FTHTTOTALGOAL">
                                <a href="#" class="redirect-item">
                                    FT &amp; HT Total Goal
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/OutRight.aspx" class="sub-menu-item " id="sub-menu-OUTRIGHT">
                                <a href="#" class="redirect-item">
                                    Outright
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/HTFT.aspx" class="sub-menu-item " id="sub-menu-HTFT">
                                <a href="#" class="redirect-item">
                                    HT/FT
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/FGLG.aspx" class="sub-menu-item " id="sub-menu-FTHTFGLG">
                                <a href="#" class="redirect-item">
                                    FT &amp; HT FG/LG
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/HomeDrawAwayNoBet.aspx" class="sub-menu-item " id="sub-menu-HOMEDRAWAWAYNOBET">
                                <a href="#" class="redirect-item">
                                    Home/Draw/Away No Bet
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_TotalBets/NumberGame.aspx" class="sub-menu-item " id="sub-menu-NUMBERGAME">
                                <a href="#" class="redirect-item">
                                    Number Game
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/_Forecast/FC1X2.aspx" class="sub-menu-item " id="sub-menu-LBL1X2">
                                <a href="#" class="redirect-item">
                                    1X2
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/ex-totalbetsforecast/ForecastScoreMap/Index" class="sub-menu-item " id="sub-menu-SCOREMAP">
                                <a href="#" class="redirect-item">
                                    Score Map
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item" id="menu-TRANSFER">
                    <a class="withripple menu-opener parent-menu redirect-item" href="/ex-main/_Transfer/Master/AgentList.aspx?v=2&amp;adbt=False" target="main">
                        <span class="txt-item pull-left"><span class="icon icon-transfer"></span>Transfer</span>
                        
                    </a>
                </li>
                <li class="menu-item " id="menu-VIEWLOG">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-viewlog">
                            <span class="icon icon-viewlog"></span>
                            View Log
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="" data-url="/site-viewlogs/Setting" class="sub-menu-item " id="sub-menu-SETTING">
                                <a href="#" class="redirect-item">
                                    Setting
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-viewlogs/Status" class="sub-menu-item " id="sub-menu-STATUS">
                                <a href="#" class="redirect-item">
                                    Status
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-viewlogs/Credit" class="sub-menu-item " id="sub-menu-CREDIT">
                                <a href="#" class="redirect-item">
                                    Credit
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-viewlogs/Login" class="sub-menu-item " id="sub-menu-LOGIN">
                                <a href="#" class="redirect-item">
                                    Login
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item " id="menu-ANNOUNCEMENTS">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-announcements">
                            <span class="icon icon-announcements"></span>
                            Announcements
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="" data-url="/site-messages/MessageHistory/Index?messagetype=0" class="sub-menu-item " id="sub-menu-NORMAL">
                                <a href="#" class="redirect-item">
                                    Normal
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-messages/MessageHistory/Index?messagetype=2" class="sub-menu-item " id="sub-menu-SPECIAL">
                                <a href="#" class="redirect-item">
                                    Special
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-messages/Announcement/Index" class="sub-menu-item " id="sub-menu-SYSTEMUPDATE">
                                <a href="#" class="redirect-item">
                                    System
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-messages/MessageHistory/Index?messagetype=1" class="sub-menu-item " id="sub-menu-PERSONALMESSAGE">
                                <a href="#" class="redirect-item">
                                    Personal Message
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item " id="menu-RISKMANAGEMENT">
                    <a class="withripple menu-opener parent-menu ">
                        <span class="txt-item pull-left txt-riskmanagement">
                            <span class="icon icon-riskmanagement"></span>
                            Risk Management
                        </span>
                        <span class="pull-right icon-arrow-right"></span>
                    </a>
                    <ul class="sub-menu" style="display: none;">
                            <li data-domain="" data-url="/site-memberinfo/WinLossLimit/Index" class="sub-menu-item " id="sub-menu-MEMBERWINLIMIT">
                                <a href="#" class="redirect-item">
                                    Member Win/Loss Limit
                                    
                                    
                                    
                                </a>
                            </li>
                            <li data-domain="" data-url="/site-memberinfo/MyThresholds/Index" class="sub-menu-item " id="sub-menu-MYTHRESHOLDS">
                                <a href="#" class="redirect-item">
                                    My Thresholds
                                    
                                    
                                    
                                </a>
                            </li>
                    </ul>
                </li>
                <li class="menu-item" id="menu-CHATBOT">
                    <a class="withripple menu-opener parent-menu redirect-item" href="/site-main/TelegramChatBot/Setup" target="main">
                        <span class="txt-item pull-left"><span class="icon icon-chatbot"></span>Chatbot</span>
                        
                    </a>
                </li>
                <li class="menu-item" id="menu-SERCURITYCODE">
                    <a class="withripple menu-opener parent-menu redirect-item" href="/site-main/Otp/SetupOtp" target="main">
                        <span class="txt-item pull-left"><span class="icon icon-sercuritycode"></span>Security</span>
                        
                    </a>
                </li>
                <li class="menu-item" id="menu-BACKUPDOMAINS">
                    <a class="withripple menu-opener parent-menu redirect-item" href="/site-messages/backupdomains/index" target="main">
                        <span class="txt-item pull-left"><span class="icon icon-backupdomains"></span>Available Domains</span>
                        <span class="new-version">New</span>
                    </a>
                </li>
    </ul>
    <div class="extra-box">
            <span class="icon icon-user" id="user-icon"></span>
    </div>
        <div id="carousel-banner" class="carousel slide carousel-banner"></div>
</section>
<input id="AssetCommonCssLink" name="AssetCommonCssLink" type="hidden" value="&lt;link href=&quot;https://stcdn.b8ag.com/bundles/common/common.min.css?v=20240124&quot; rel=&quot;stylesheet&quot; type=&quot;text/css&quot;>" />
    <!--[if (gt IE 8)|!(IE)]><!-->
    <section id="account-info-tab" class="accountinfo-container mCustomScrollbar" data-mcs-theme="minimal-dark">
        <iframe frameborder="0" id="accountinfo-content"
                name="menu" marginwidth="0" marginheight="0" allowtransparency="true" class="accinfo-content" scrolling="auto"></iframe>
    </section>
    <!--<![endif]-->
    <!--[if lt IE 9]>
        <section id="account-info-tab" class="accountinfo-container">
            <iframe frameborder="0" id="accountinfo-content"
                    name="menu" marginwidth="0" marginheight="0" allowtransparency="true" class="accinfo-content" scrolling="auto"></iframe>
        </section>
    <![endif]-->

        </nav>
    </aside>
    <div class="content-wrapper" id="content-wrapper">
        <!-- Searchbar for mobile -->
<div class="top-search-bar">
    <span class="icon-search"></span>
    <input type="text" class="top-search-input typeahead" placeholder="Username" data-provide="typeahead" autocomplete="off">
    <span class="icon-close"></span>
</div>
        <header class="header" id="header">
            

<section class="navbar header-nav" id="header-nav">
    <span class="icon-collapse icon-hamburger withripple" id="hamburger-icon"></span>
    <ul class="nav navbar-nav list-top">
        <li class="maintenance-box hide" id="um-message-box" title="Maintenance Notice">
            <span class="icon-under-maintenance"></span>
        </li>
        <li class="switch-mode-box">
            <span class="switch-mode "></span>
        </li>
        <li class="feedback-box" id="feedback-box">
            <span class="icon-feedback"></span>
        </li>
                    <li class="visible-mobile"><span class="icon icon-home"></span></li>
                    <li class="visible-mobile"><span class="icon icon-account-search"></span></li>
        <li class="hidden-mobile datetime">
            <span class="icon icon-time"></span>
            <span class="txt-top" id="clock"
                  data-year="2024"
                  data-month="3"
                  data-day="8"
                  data-hour="17"
                  data-minute="9"
                  data-second="10"></span>
        </li>
        <li class="hidden-mobile dropdown language">
            <a href="javascript:;" data-target="#" class="dropdown-toggle withripple language-selector-container" data-toggle="dropdown">
    <span class="icon icon-flag language-selector langFlag-en-US">
    </span>
    <span class="language-text language-selector">
    </span>
</a>
<ul class="dropdown-menu list-language" id="language" data-currentlanguage="en-US">
        <li class="en-US"><a class="changelanguage-link" data-value="en-US"><span class="icon-flag langFlag-en-us"></span>English</a></li>
        <li class="zh-TW"><a class="changelanguage-link" data-value="zh-TW"><span class="icon-flag langFlag-zh-tw"></span>繁體中文</a></li>
        <li class="zh-CN"><a class="changelanguage-link" data-value="zh-CN"><span class="icon-flag langFlag-zh-cn"></span>简体中文</a></li>
        <li class="ja-JP"><a class="changelanguage-link" data-value="ja-JP"><span class="icon-flag langFlag-ja-jp"></span>日本語</a></li>
        <li class="th-TH"><a class="changelanguage-link" data-value="th-TH"><span class="icon-flag langFlag-th-th"></span>ภาษาไทย</a></li>
        <li class="ko-KR"><a class="changelanguage-link" data-value="ko-KR"><span class="icon-flag langFlag-ko-kr"></span>한국어</a></li>
        <li class="vi-VN"><a class="changelanguage-link" data-value="vi-VN"><span class="icon-flag langFlag-vi-vn"></span>Tiếng Việt</a></li>
</ul>
        </li>

                    <li class="notification">
                <a class="icon icon-bell withripple"></a>
                <span id="numberOfNewMessage" class="number-msg"></span>
            </li>
            <li class="dropdown setting">
                <a id="btn-header-menu" data-target="#" class="dropdown-toggle withripple" data-toggle="dropdown">
                    <span class="icon icon-squares top-right-menu"></span>
                    <span class="profile-avatar">
                        <img id="userPicture" width="50" height="50" src='data:image/jpeg;base64,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MbhCBtYdVGOg64J5IJqjDdTXF1vsIxFJtKlj8zKpABUk9QOxxxn8afq88LXTSQBRDIxZhGxKliT2PI6/171Qk3296slvOR5bAo6n7p/+scflXp0oe5Z7/wBaHHOXvaHfwy2898skMUi28yxXqt87LaNESkkRb/loSv8AdPUHrmvSdPNtpevtpNtHfeVeanLcw39uoliDN8z28xbOwjLjb/dHBryfw7epew21rELq0ubZGCiKbfHcJMvzyyg8A785XjKuccgA+jaDdvJorROZo5bS+jiu7YutwFztClT1VCq7CeSu0HqKWzsVe+pc1K0aLXpr2XUG063njSG1vbeWR7gSFDGAingOMdCCNvQg10ljaWmpXSztEt3bTWygTxhhFcoSNwOD/rNyqynGAM1m6paavcNfCG8SYnEmnwSp5f2aQLtYecPmCsCT0yD3q81oEiSXT3Imt7Y2375iRNHkMysBj5jz84wQST7VTjF7oE2jpLGSC3jLpYwrE10iERRKV+YYy46nkj3rLurSz/tJtVuNMiuriBSWvEVGF5Gc74Qo9CoAz3wKtafdrBNDKiOpfZiMncflwQCe+MCptYe1fV7t7GS3KtOXlijAGyRhmRHHZg3PvuFZezjzbGvO3Hc88utBubLR4NXvfD2k6hqtqTbma1VoZvs0mNpkUYAdVYhl5HFLdeH1uPDy2mm2Edp5hli8yO4dFuIeD8qA52k5U981veImTT9OFyGmkW1tJIikszkzLwxVmXJLAA84zjIzWBostq+sQz8wiOEC2vHbaHLhRsKdAdpQBictt555p8iTRHMz/9k=' alt="" title="Click here to edit profile settings." />
                    </span>
                </a>
                <ul id="header-dropdown-menu" class="dropdown-menu list-setting">
                    <li class="profile-group visible-mobile">
                        <div class="profile-avatar">
                            <a href="/site-accountinfo/ProfilePicture" target="main" class="img-link">
                                <img id="profile-avatar-image" width="50" height="50" src='data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAQCAwMDAgQDAwMEBAQEBQkGBQUFBQsICAYJDQsNDQ0LDAwOEBQRDg8TDwwMEhgSExUWFxcXDhEZGxkWGhQWFxb/2wBDAQQEBAUFBQoGBgoWDwwPFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhYWFhb/wAARCADwAPADASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD6Au9NJU5XBz0Ncnr1lLbaouB+7YdTztPuK9WmtQZC+0FemD6Vla1pNpK8c6opkVcAmvQjOxjKFzkNPtg6gIMbf0q8tmZsAEbl5wO/1rWh05UU7Uwc+lRSQy2l3vSPaM9DRzBymJqekrdIttcIqrnrjmrw022gtY1hiVTGP4R2rqNR0m21GGJ85yoJKN396oXmnSWvBG5R0x6Uc1w5LHOeXsb0GetXrMZXmnSxornd096aZ44kJBXH1qidi6sIZetRtBg5qlJqMcLKzbirdDReatsh8xUyvcAcmjlY+ZFq4UKuSRwORTbW8jW1eQZLjjb1rETWXu2eFcJuU7M9d3pWYt9cQFgTtkB5Bq1TIdRI7WbVUj2F+rAfhXI+NLgXVwFiLcHLE9B9KfPqUkkexlUMOc5zms28kaZvmx0pxhZkTndWMSYPvYcnJ601Ifl6Vp/Zd3IFSLagDpWxhYzYrcA5I5+lWYImDBh096smIBcYNSQQMR9KBlq1sY3TzCRn27VN5AZfKwNw706xj8uLYO45qfGxlKgcCs2aorSaaFAJByRQtuwYADLA9RWlNK7Rq+0Zxg/41GqGRvX0qbjsiS3hKR/PgHrjNBZpG2nhV46UsMDCTLdR096txxx7tx44/OgogVdqs38PvUbJn5h096mnV5JulMKN90k4HTFABHIqA557VG25ug47YqQRjHQ+9Twr0G0UAV1jY8dasPZShQ2T7g1KqZ6kbvanuzGPy8kKKnUZ3XDjbjbVa4tlwdg5qTcw6UeYx4Irm1OogjRQvK8+lMuIBLIqrFuBGWU9Qfari7epqaE4OQKBWIbWCG3tW2IUzzjNZ186tIwc9uCe1bEyCQYGVJ7dqxfERjtLaSR2XIHQdc046sTOO8QzlZTGknfkiqEZYxqjH7x70+4kWWZjLjI6mlsIzdTeRCQp65PNdSVkcrd2OVFWVY3+YDkFu1TX2WjMaplR3A6e9a1tpY+zgBt+OretO1K0WO3RVUBnBDEdqm6uVyuxx9xZOHHPzdmHenzQFwryAbsfex1q/KskEm2ReM45qXYJGztGMVpdmfKZH2UlRjp60xrfb2rajtwkmBznpTLi256fjRzBymV5I6Y5705YGJ4HFaDW237oyaIYG3d807hYprZZ6joKmS3A7c+lW/KZTgjipVi780rgkV47YYGDipI4Crc9PpVqNMjGKlhjz1zx0FSVYqfZ2I5X6VLb2x6Yx6e9aNrhR84/Cpyg2hsd+MUrlWM+O32nLd+lK1v6Cp525+h7imRkluaYEaw5PAoaM9cDFWlUntQwGOlK4FMxccgUnl4arTISaTyvmz0oAqsvzZHanAN/eJqztHTFLsULkmkB18luw5zTArDg1eWRGIHfvT2jjauXmOopxpntUGoaddzyK1vctEBggAdT7+1X1j2yYHatK1RcYo5rCsUILS4ZcSkKQOSDnmsfVtDna3kjaLfK+cMB19/aus2Beg+tPVC75Azx3pKbQctzyLXfDa2WnPPMkxlQ5Zum7/63+FY+mOtvyu7ce+K9l8UaRDqlkIZflKsGBH8j6iuL17wtCl15kMhhWTgIq/KD7V006qaszCdNp3Rzy6lcLHkPyRgDtUK30+8s/wC8yO5qxqGnT2cmyZO/B7Gq6wkpna23PXHFaaGepA7NNIXdiWPWnqrL92pVtj1FSw27s21VLewqhWY2OTcwH86sQxMWJVSwPBxUawsr8jBFWrZzGMKvJPOT2qSgNoUwCvB9D/OpFsxt3DH0q5vimCpnbtHFPjAbjNTcdirb6ejR5dtp7ZFNksvL+XqfU1pKi46ndTJgzHOc0XHYzRbtjgdKfDD82egq6Ijjp+NHlgckUXFYrMoGKFL59B7mrgVP7mKhkIHGAPcUDK7RszfN/KpI48U5W9KkjRm6UCGlBt5phjPvVzycAZpJmijGWYcdqQymyEUmMDLHFE13jhVUe9Ubh3dvmYn0qrCLEs6JwgDmqk8zueuPwqKQEGmd6fKTc7yGcjB7Vbt58jBBPoRWPLJ5UZbv2qr/AGpOPkGAO+K5OU67nVx4bnNOsp3W4KN93sR2rG0/UyxBZiCBxnvWxa3lq0YM21WY9R0xUtWGaKzrt6g4qS0kGMCqEbWzHEMi59AetTW9xAkmGZc9+amwGi0fmLVDUoYBbsZmCDHB7/hVr7QeACBWH4qeRpFw5Kjt70RvcGUrpLeaQZiUqv3dwz+NTRwxGHayLt9MDFZizkSfNVpbjK9a11JK9zoWmvuaFfLYnt0/KpNP0K3hbcdzNn7x7VPDKM4AqU3IUYKtijml3DlQl3pNjcRr5sS5XuOtYHiCxsbXdIkyxqvVWPH4Vf1jVFgjYq3boDXl3xH8Yy6bpN1dtbvKscbOFTlmwOgHenHmFJKx19u8Eiq0E8MiuMrtcHNW7YZYA14JrVxfaN4Jm1mC/jt9cVFukuDIFhMqp0YdDtyBkdutd38PPGerf2ha6TrqR3v2uUj7bDKM2hwPkkHfLHA79eopU8RGauE6EoOx6YrFcc/lQNrMSzYowQcEY5p67e4rYyHxqjKQck+ooaBE5zuqSPO3K46dBSMxOSE+ozSHYqSIzN14HoKjaNelWsHb9Txik2KoyT160xEENsWXOKsKEhHz04TIOVXAWq+2S7uBHEu5ifwA96AI7y6JOI1+WqZ/eNyee1bEmjyxx796kelQnSpTMM5CewpqUQ5WVIdMlkVmx0PAFEejXDSHzUdV9VANb9mqWzAfdQ8YI71eUBlz61DqNFKCOQ/shjNjB2Z5Y9cUTaZZmQiORsAcA4J966yaBGUgrjNUzYQBuFGc+lCqB7MzLicrD93kdMisolvMLEYycmuw1qzRLYkAMwFcxqQaNVDAZx2qEzQS3kPGTVxbjnA/GsmNytSrMC2FoA0vtBU5UkH1BqaHUsAJJID7tWRJOR3qpLMzNxRYDs4dQQqu9zuA+X5uDT76bdbszMScfKetcba3sqLhhuUdj2p76nJjGSPxo5RXNNp/mxmpI5+M5rDkvQec01r4460WHc6a1uAT1qSeddvWudh1CIL1IP1ouNSVVzk/jSsUmO14wO25zyK8o+OmorB4TultVgE6p+5eWPcFbPHHfnFdj4i1hVBbcPzrx/4r63Jez2uk26JJNeXUaopfHAYMxPsFBqtlcib6G7oz2DW9r55UWcgEc1tIokSJmX94ME5/vfLyR7itPRdK0nRda0/UbAhbaC4TbGJRtlQn5EZv4mGBwRkc9a4zUzPJef8AEuie6aWQyLbkYfPzEKVHsAfwqrpFzqEd81s121ncWN3KPMEIc4jxvIGR83z4HcYrzotdzvk7bo+rGweV5DDIb1B5BpkijHNef2nxO0DQPhZca3rEzSf2UTGsFqPMmnUn92QOwJO3J4BWta3+InhO6sY2GrQxXkmlyak1nK3zQoqs2126AsUIGMk9hXoxmmkzz5R5W12Om5T7poWRjIF3ZLVyXwa8faZ8RvCK6xYwtaXUXy3ti5y0D4z8pON64I+YdM4PNdWJLS2mQ3l9a2u44Tz50j3Nj7o3Ec47VpdWM1qTTNIrbDUfC8559DVuZTkbsdMg9cj1z3qIgOucAn6VKkXylRvNeTaoJ9BW5otj5MW8/eYfMapWyBG3EjIq5HOQRtNTKXQcY2LWAzlSOAamjh9RVWOb5sseanW4xxWbLK19HI0mFX5fWrNr90AjpSMdxzToSAKG9AsSSKDT7O3R25PPrTGOaLeUrIMNikA3VkVn+X7ynqT0rPu9BS4jM5dQMZG44xTrudXOShJ7HPeoZJXk+Xn8TTV7DMTVLRYV4xx3FZjNt4GPrW9qUbuuHKkdttYU8LFvlH0q0SQySkiqzzEMcVcWCReCPpVO8gkQ5A3Z6YpokjkvCi4J/Oq8l1u6MM1DqEbJyay5p8MQKolmws+88HgelElxs6fqaxEvPLGC1NkvAy5z3oBM20uwuWZsn0qnq2rhIDk1kz3xQHB6VzHi7XVtrd2dvpz1pWDmJvFmsosLEt74zXkUGvxah8YNMjAaRYi8SlFLESOu1OnPU4z70njTxFNcqwjIK45ywwOcc1B+z9aRN8XNMuJtxSa4fGF3NuWNiPwyQM9s1lWko05PyCjFzrRj5nqGveJbnwhcW2radbKbuOQW0sNzHxGTxx3OdpzVf4ea9Dq+kazNrCNHeXWsNdmS2wFVX+YoM8LzjrwcCtn4iWVrqUl5aNCwXEbqzyh2Ehzlieu1Txk+tcH4d026tND8RNqBZNHjtvKnnCkDdwFKkcnGSeAc8V5UeSVHmWktPzPWlzwrqL1jr+RifGDUY9Gm0y/to90lnI0gwCieU6MoV1P3juZjzznmqvhG7W9jW/uUZ0h8i0HmtljDGm1Rg9eMkH1qb9pSKODRhbCZRD58aW8IDMoQL8zpIfvDleCcgmsfwaiXej30O8745YVjKN8px8uB6c16NKSlTTR5taLVVpnQ/D/W9U8Hadea1odzIuqaMJERJDvzJuOxQp+8XLfd6EA57VZ1i91XX5kj1eW3l1G5Q6qk7OfLuJm4ZTjp6Z6EgAdKyLm/vdJ1W6l/s0m8a+LXMm5SrtswpUE8DYAAR1Jb6VnXGv316s621pJFcQKYZCcEwL22AdMkDj1yad29Q0Wlj2r4CfFx/D1rY6H4oM0mg3EZdLzyndtM2jBJK5BjJwSOo6juK+g5JGiMcsMizQzIHjdDkMpGQwPcEEGvkK41DUdJ8Hxw+XFbwyW9tcqIjkvlShcE88lcFT1x0r1/9lv4lWOo6XZeCNbeO1mhxFotzLPkXuWz9m56MoJ29AQMdadOopXKnDkaTep7HDIzt1/CrkbYqa4sIoY1YsSzdMdqWG2yKtsSBWy1W4Y2PIpkduoGe9W7UAcdKm47DRGwOKa2U4NWpGA+lV7rsR0pARM+B1qCa5CHg/lVe8uAkm2k+ztcKZIwfm7VokSWbOSJmAkHX1qWS2tx8wcnPY1UtYxwcsTUl8StvuDZAPIqRhf28BjAXO7IyB3qrdQW5jGxADjoO1VZLw+ZjJOe9RtcAEkn8qqwhJoQMAjH1qCa0BjII5+lOuZwzDDE/WpI3kZMDk4oAytQ0+GdcFRlq5PUtK2XD4Dbc4Fd1NEVbMinnpmoHtoi+9hwemRVXE43PK9ekXSoTNcphOxYdfpVFdTguYQdyKOuKp/tJaxBL4ij8MW0gR7SNZ53HQs4yF/BcE/71eeeH/ECJH9nZ2k8tsbx3p3Mnoz0a8v40iIEq46V5j8TtbF3bzW1vIu5WK7vT61Y1zXYQrTeawbOdpbFcPrks2pW67JdzTSeYx24IGCR069qUpJCs5GDHIbzUoNP3+Xu3FickPtGc4/Gu/8AgbaG3+JukhmldROziRiQN4QlSMHIHSvPby0vdK8S2l1PPCIfKO8eYFyc8/KeSOR9SK77wTJcN4o02a2ukhkgkDrO67gijqSOM8E8VyYh80Gl1R1YSKjNN7pnuPjrRTBpeoax588F3Dbh7eRWbZPHyP3gAPmcnaQBn19a831PV08ReHp7CGSRpLgxt5eQwjmiKsyleiOcD6j60nxH8Y2ywx+VdSLcTMzt5bMkOMfeUEnA7/UivH/+Ei1eDXrzVYnjH2i5WWURDknaFDL78dfUmuLB0Jum+c7sbiIKouT5k3xA1eHUoU0tb1rzyBPAWBbEX731PUY9PSui0HxH4kvNS0/VoLSG1i0uJY98MKxpLL5e0eZ7Mq9DwB9a5W+vgmqaqYtPs44b6SNraIRAtDt5/wCA5JJI70/w7PfPeTly06nl4TyGJ6jHsMfSvSjBKNjypTbkbuteLkuXiLzSJE+7bbuudo64Gf4RnIrQ+CYtvEOsX0Fsjq02MqG+QED5mwe20nv3NcHq1sEkcrNMqZyq90YjkZ+ma3Pgzrf/AAj819crnMbhIlJP/LRSvUck9/woqRvBpFUZ8tROR6B8dLw21na2a2rSGG2jTCgnZHGWYlivrkDPsa4vw+skXlXUDKjMVaNoSQYtuGUox7g7TnsRW34dtdY8S6w93HH9smurV5ZcMSHB++SDnhV5I9OlbXgfwPbS6XZrHcXN9NNIF2xKEAjLBW+Q/M3BTBX17HIrCMo0YctzeUZ4ipzW0Poj9mv4mat4sjk8N+Jp5LzV7a1FxHeNCFNwgxv3leCRkEMBzk16zCSF6Yr50v8AwIvg22tfEHhLW7jR9YsbZZFtWuAyyhQd6Zbk7sAFeQefWvcfBfjnwp4q0lLmx1e1guPK8y4s7mQQzWxC7nDI2MgcnjPFOhXhVj7rKrUJ0naSOgRxuxUqsB0rzqz+M/w3luorefxD9hlumC2q3sDRG4U/dkUc4Q9icE+ld8HIUHgqfusDkH6EcEfSt1Z7GexNvzlWpDgrg1XZ+aUyH1piKmo2rGYSR4OOtW7BWRcsetM35pULZp30FbUqLN5OVdsY6Vj6prLGXyY1wnQn1q/cXSGEsCOen0rk9YdPMZ0PfgVSQpFyS4yu5Sfeo1uXPGTWbFKezD6ZrS0iH7VJtUEt2HrTJLFsWYjnvWkzzQxK+Ar9ACOorZ0Hw2kkPmTHa4xk54FHjqPR9A8M3/iLWLkx6dpds01w8S7mKDsq92JwAO5NRzK5dtDk/FWvW+l6BdapqMirb6fA0zu7BQcAkID3LEAD61458A/iBrHiLxzeWOv6rLNPqkPmWtu+Fjtwh+6ijodrfjt9a4f9oLx/H461PTbmwguLLSrOAiOyuHDFZyx3yErwx2hAD25HvXA2fiC60zWLfU9PleK8t5CYpByApUqcjuME1pbQ5pVPeVtja+ImuSa18TtZ1CKZTFdX0yq0ZztjX5AQfcKOawtJZtsgRsbXGMehGefpTNDtyNKnumICZKg5547mrmnwgZVfvOcuewAHSs5MqKuYN9NJNqcsbswCvxvOAVJrTaKWK5ES4HmABQnHHbHocVn63JG+oEPu3s6KmON2OvP51avr63N5gMVmXPyK3T3NZTlob042kzgNbuZNQ8UXF1KrHaRAmF5wnXI9a9L0NJ4VjbO1Cm1nc84x6+o71ymu3e+6kltZWVCy7xFGPnYen4/nXS6VeHUbNC8T2+cqyvgsuB+VRUeiLpaSkctqt1JdeKbi3EskohgCRDzCfvHJOT24qpZ2xjvrkSfdgby4yON0mOn05NMh8r+09SmeZfO28OT/ABK2f61bspUjKTSLGQ8vmtGxxk4IO4+nJPrWsexzy7kl5B5FxNPHJ3GY+vl5GAB+maq2eoyWdwh3PGWYKwQc8nk/QVIH0+bUEkuGkZMllK53Skj7vqQMdTVvT5bZ75fKt18sg5dlyyr3Iyepxj6D3qyLakPiK6gjJiWTcEIKJgA4xn73ej4ZrfX3ic6Zp9st1fX0ywWcLOqh52BCBi3AUZJJ9AazfE2oxQIxiEBYErCoX5hxxz247muk/ZxSKx+I+m3utzw2cE2n3N49xMw2xRtGyh8nuB0/GoqStBs0pK9SKPUNJ0ZfAF0NKXVI7yMWdxqGpalACqvFGvIUfwgyFgg6vweldF4Jt4/D/hu21PUZbiyn8lJ4baRPOdVYjeTt6KXYdvUDkVyX/CSWvivx1rGi6bALbT/EE40tdSZOIbSHYdsa4+dgAGx6P9a53X/EXiy8+LhsRP8A2pd2iSWRtHiNtGtuj5Zl+bksxJOerEbfSvP5ak/i9Welz06fw+iPXbPUbvxTfLPbSRyR2FyyzmZQ0flhSMW6sMBd24M7YZuMdeL3irTdGutL1GzsbCC4BkRozIqB4W2BTJGTkybM7tpwwGBzxVHUP7DN5Do1/o8lnJbyW9zHaQxtE1lkB1L4bscjJ7Z7Vam0qw0/X4NTj1O6mt7qdJooMhh5xcuDk9QRxjphQO2KI2toi5Xe5T1Dw55HiRdTvNBN9eWYi/s2dgXEinCspXgFl3HBbDcgZ713em+IJPAtzDquu6zqT6cs0VrAzsXgjt24SF1H+r28dv4Rk8Vh2Jl3C1vbqOSwmXpbRsySAlvvbvmVsnqc4PpS6hper21vKq6n5lheRgsypu8wAgYZWyM9iO/PtVcz2uTypapHvehavpOu2AvtG1G3vrUtjzYH3AHrtPcHHY1dkiwAVP1HpXh/hG9vvCtrqCeFIoIrq4tleO1v9zW7MOhKrhkOAQMknBHUDFeteBfFekeJLia0sxcR3toim5gmhK4YgbgjdHAJxuHFdkKikvM5KlJxfkaXlv1xgU9QU5NW3f5+Bu9qZcSuibHj256DHWtDM8q8C+PdF8R27W0MzLOIw5Eq7UHqA3fn860haQu2ZWAxzg9K+cfhtqEsGq+d5LorYDMOFz3HNew+GtTkuoNomO3JCsGrWxlGd1qdTb2hubjZDCoDEhW6Amuo8JaU9lme8CgdsdaoeFdSsL/T47W9H2fUVJUEfcmA6MPRj3H5VZ1i8ezj8pGkmJHysoOBUPXQ2StqdNLqFlAy5u4YmYZUFxk/hXl37VniGC7+BuuW8jxsqyW5jZUwTIJlx/WmXl/I7sShjLnDnHJNebftLX09p8P7a3WfbDdXubnoxZUQsvHX738qagkTOXus8K1AhV2+Z8yfPgjpnFYsZWa+QGRd7ScqF6Z9/wDCprxp7n/SNu0NnJyPkHbI7cVR0tEuNUhjilbaE3A455OP61UnockVqjqI1jXT/s5KbZMgZOAT6UtrLtDD5d+NuMdRmmXcKwMkW6NkjfkFMqMYxgflxWbqU5srOa/di+xuFxgEnua52dUdHdmZqVzNPrEj25J8u6VUZ1HDAbSQPSptagkulkjhQs8aEs397J7/AIfyrP8ADN+k/iu5MjqN8Wcpyc9eDXSWt1EVkYsm5iASf7vtWVTRpG1PVNmdY6NIpaW6jk3JGdu3GFPQU/RRcm4MKqw3ZdnOflPTOPf+ldFpskd1ZSJujKoT87IfnG04PqMVk6HBdSwzKiyIyNgyMMADofr9KUotjUopO7OA1VAmvXEMana1wARj5jgjP4GrrzRmS4WUmRWc+QhAAUdMH1J/TitHxpNZW90iW1uvmXE4Mt13O3B2g+ma52/nSJZ5Im3R5Cscd+TgL1Izjn1reL2RyyV7sZJcT/al3oYmQ8YYAAdAc11Pw1meGe+1qaKNrfR7P5VJB+d/kTOeGxyefWuT2SRKj3ESncMgq2SBxzx7flzXQeG9Nu20a6vbySTTdCkw7sw4uNvRlXqcc4J4570prmWg4PlldkPiiWDU9Wml+yx5V1Zf4R0xhu5weAKXUElbSI2gvIZGKNGsYlX92p5Oexy3UVFruqadJbQWenQyx2yzLMzzviW4AHVj17+2Kwbr7Jd+WJryCHs+MtgjoAB1pqPQUpN3Z6Z8K/EWmvpMnhfUI5ba8Uy3WnassxDW1wyLGw8tBllZcAc7hjj0qr8JNFufEvxCuC1zdT6iES400y3BjFzKkgbyzIQSDtVihII3AZ61l/B0eErz4g2dtrv2uZppV+z3AmaKKGYfcMgHLBiB0IwcV6VoHhDR9P8AGQkklvX1O3u5DDqumyFVXjeqEMT5m11UMFxw2Oa5ak1C62djqpQc1F9LnoHhr4leHPFEep3mp+FNSsYLdjaNrKhZTLEeCJVGCV3D0PTHtUeim9uZtT8PXOlA/Z0FxDLG2YPs27aA3dfMAB5H5YNcv4F1jTtVa+1ldRMEem3sjaxbLD51vI82GMqg4ZV8xWPGcZJxxXW6hewxaK3ia2mhEUdqou7qzcLHdQhThyoPJicjbjkhifUVz8zT2Oxe8tzT0NrVdPiMupySm3icROZAoghZjmNgM5RSTgnkZ98Veiure1/0Ga/eGCSTzgzTq4YBMjaCMOpyCVBDAc9sVxvwtafTo0vpLtJ0ureOPUrVrkP5L9RuwNytg8jnse1dhZtCLVbmSQ3VvqEnnsl7as0iqoIKIF4dkI52/MynpmnJq9xwu1qjUa4jiYmwujFM2XFuG8yPIwGx045Htz2qtq19dGY2khNkFieO7WEsscgYcsswOVHB9u1c94oa2tnMun2kFrCs/n6lb4Z0mRgu6SEjO4DKMePlOcgYNNvn1D+yWm1OPdbW5YRQwxs3ybhtUIDzgEk9VYE8DFVGa3JnF7Hpln8WL3StHaK903+1ZIIgkAhnW3kZgMKjFvlIOB8w59jXd+GfFUPijw/DdWjBZQB5tqXDSW74G5SB1Az94cGvmqP7BeaobHiGZQYlcyBtpPzEbOBu6HJOfTHFRXNrNaakrnUfmTcXkt5CsqqAduWU5xjI45PHXqeqFU5ZUzldNeW+0uNtOtpDI33vNfbsPZgK734bzXmn23k3YMS5/iPOe9eW2esT2kqvY/K2OT0LH3rag8fTJsiuLJW28eYrHcMegrsucCPeINXCqrdWHIqy3iPUHjLJIxYqQP8A61eLWPxHt1jkBt3Zk+6Xfj8cc1V1H4qeI5MR2MemWKLwZfLMre2Nx6/QUaGnN5nsLTXbb7m5lSKONd8kkzhEUepY8Cvm343eLJdb8dajqFm7TafFDFZ2TgHbNGhJaQA9ixbr25rW1LV9b8QwKut6vfahCrB0juG2xg9vlAAH0IzVe7gsIIfOvoo37rGy8Z7HH+NFyHqcBpthqeq6fJciJvswRmExUrvIGcKOrfXpUfhUhJE1B3AaQ7I4g/zLjqSPTt7Yrrry+mvJVJZkA4VV7D0AFSWWlwSMPPiWJc8qFBc/U1DuxKNigt3NcSRon2mTD5UIu4/X6VT8VabqV1pv2aFpHnILtBHj16k9z6AV10MUaxkQwLBEBhm/iamXU8EJ8kHaZOg6s2OtTbUq55jcadq+mzLd/wBjgAhVIiYM+B1Bwe+K6DWDHb6TapYub69vZQFtox8wB5IwBk46ZrqLPR7/AFONpYo/ssJ+9cy8p9E/vfXpXT+FfBkNurGxtmj83ma6uDiSU/U8hfYcVMordmkHLZHNeFdMurTTUmvo8zM3+pgbftJP8R4/IVc1OzDxOJY1hh3ZESclj/ec+p9BXW3umJnEEsShFxvPYfyFZmsWttY2e+a/ilPO2FVPOO7H/PSkrDcZdTx34qaTP5cd9HIY44lKvEuQEBxtJHf3+tcZo9lPeGa00iNtTuJfkVI4yGGQRu56Adcniva7uKXUJGLoqwODzIoyR06HqPfpUOi6PZaZDJY6NbR28Wd00i/1PU9eBV9DLqc14J8FWmjIkuptHqF62N0O7Nvbken/AD0OcdePrXSateQTLMkhWZo+GyoYJgZ78AY9fwqeOEf6pj8zD58jBCn+X86y76PdeC2tInMCAfIv3pmPTOew607geV3sV54i8US3VnZSRR3J+UODtGBjOewOKk1PRYbOFYWd5bgDMsykADtgL6V6LfLFaRrCAslwzbDHbL931CjrjB5aue1VIFtpY4/L852KtIibthHVd3fjv0FJyBRMfwTpaXmuWzS27PZxSx/bpfMKKkauCTu5wccZ6ZNfR2s6Dp2mQ2zeHJhZ6fu+0WiNOkkcKsRggDLhN7Bs9Qdx6HFeH/CjTJ9X1WaztbyKFbVS08zMFZUcheVzlk+8CfcZr6A8G22oquZrOKCzjke4klcouUCkBohj5MKDuUcEDjPWvOxUveSR6WFj7rbMvwx4JvLGzvNW8N3ccJ1C/wB2p6apTAbaF2AZ+aNgXZc4YBzmquofCrWtNsFsPDt5A3h9r2O8utJupnAXY+QseQcAH5ih4Ir1DwCq2+lad5haV5o8NM9v5TTkktlkx8mQTj2x0rYV9lw0YHneeA7ZOFcbsY3diR6d+ahRadza0Wlc+eY/h/4+tvDU8Vtc21rfyzzvdM0gIlDuWCRsowCwI5OMD0qTwTqfxGjs5PD11odwl8EH2qzurEtBKEf7ruCAhwQQ6nPTmvZr6Ga31KK5iRpFtZDZ3MeQ5JzlMr2yrKQ9Q+MLKGRdPvdId528qSPYsuEY4JBbHU8kZ6cDoaTbe6D2aT0ZT0OyvA1vdzrBDcXMn+lQpM0kIcK3zI2MLLztOflYZyPWGBptLFxo+qzTXK2qKEneEmS5TGVeQKeGBwPl4AHIpmn6pqJjulaSGQtGwktg/wAocbRuVgT6kZ5HHXIrftXW8Vd1uzQxAOlyjL5ttL0ww75HQ9CQRzXO7wlo7pnQkpLXRo4bxrYabf3FsHRUkuCyi4gfY0jRruKFscYHXsQRXJ/D19F/t3UYLKSWC5hkTy5ppCWDAk+Uoz+Pp2716b4k8JWdyyNcXZhilj8uEwlkUvghZIj/AMs5BuIKHqDgHgCvD5vDt74J8YahY6zcCOOQGWxuPtLMt2ScRhmC/Kc8HuG611U5+47M5KkWpptHP6CdbuISxYuucltvzH29PxrYiWdI2Mzjd/snP4DtVq4u0WaO3Eu6Vl4VVIAHuegH0qKaMM2V+Yg44HQ+31r1TyB9r5Sny1Vs5xuJ7/hV+zSOPbI4O4DAJI45rMhilWYEIqK2cAnC+5+tXrSG5eQNl2LDAxH+oz0p7DNC4vBbr8gWSbqAT8qe+D3rDka6vrhnIYszACRhkn3Va6Kx8N5LSajmJSd213y/tx2H5Vca4t7KPZYRqCBgzsAfyNIZm6bo62cfnXYMO4dW+aR/YDt+lPvdQtbWMoP3eB8g+8Sf9o/5FVrrUWnuRDbLJdXEhwioCzMe+MV0PhjwDqV0FuddV7WNz8lqpzLJ6Zx0+nX6Um0txxi5bI52xe91OZbW2geaXgfINqr756Ae5rs/Cfg8T3SGWL7c4DGWQnbbW2P7xPLHP1rvdF8G2mkWKy6oV06xVcrbIQs0hwOpP3eO55qLXvGOg6farDaxrIIxiG0tx+7GOhdj941k6vSJ0Rw9lebsUH022sEV5EF1M2RHK6BVUf3UTsB6nrWVrl5I9v5bXCwln6N1Ze/9OKxfEXi7ULxpESTy5XXkRcbfZmrHsJJVvPtlzH5h42rIx4I6HHfHbPr3oUW9WKVSK0ib2m2dnDb/AG/Wb5yvLQwRxFix7Z7H/JOK53XLmOWeS8m2sxOQoHyAdkX1P6Dml1nUn8/bIHmnmcBYVBzg9SfQew698UaPYpb77zVI4jPITtjIztH8vw6D3q0jGUrkNjp813E013vt4XI2rnc8n+0Sew9+nao7q4itbdoYSxHTzMct7+9JqWr/AGm4NpaEMygEnafKUHp83Rj+gqrbWczXDPI2+U8mYcxgAfw59utUSNkaed/LQybWxhGAG4+rY5P07U28l+xf6LZp9svDgHHKx9hu9eew6nrV6C0uJ5ktrD91GxO64YHkdDs7k9cntWf4ibTdF0ua2R5Jpo0+do8eYGbOAQO/seg5NS5FKLeph6mPJlZ2CzTXUR86Z3w7ZPyhSOFjznPrjjisS8kvriWO3Xyll8v99HC2BJxwc9NnBwB35NP1HVILnfbRxEZjBkzjKZ4GwZzx0ye1dH4Bsri9Zlu4vMj8yPcnBLAEBgP7rjKt8uDtAxXPUqKKN6dPmdjrfgtotto+lyaorwxExMk0qQJMIpiOj8cgAow7ZzXW6XqtyutQw3EsM01qF1ELPFyi/MgeNs4ZdpxhsdcjpisTUlsbDwmjSI6XBmXyDaFZmk2jldgwCVDHcSckKTnNaFgbseIob27u9PFvFYizvi4wvmh8Da5wMEEEDoTxXJFObbudl1BJI7LRXs3ms4Ybn7R9sjlu4XWVsKjENtTcOVwev8JJHIIrb85hOHlaOUCRYkIARoVbPYHnPy8e/FeceHJ72xuNLZoZUMdxdQ29vI4j3tI+3Yw56FSVAxxj146ePU5Z77ISFbe8hD28r4WZ5lJ3IUP8Ue09z1AwOtaaIIts6e4ewWdLl5Nq6jafZ5ZBkCOSAsMsei4VupPaseDTY1W6e3uzELl/MttrblY7AS2OjBwAcEDv1zWjBLBrHhGOYXDw299cRocAHyxKMbsKSCcgcgkZ4rjry+1XTtPubrVLbT3ubbfZSwWcrlWzKpjIBGQhRgCG+ZGOc4rNpGl9g8SWMsFxpM2lRxWEkNww3jay26OCghlUciMkhlYcKevWrfgW+tfEegzy2mqW9nqMZ8uaGF45HxFIdygNn5HUD5uoGOh5qTVba3fxFpd2baKWyYtbXTeZ5UkMjLiMSnPMbsChVgV3bW9K57xN4DstI0m0vdDe0tdl8zXE6QkeU2SwlQKfk53Kycrke+BOkgvKJ3st3Oq/Yp4rd7O6JFv5v75ZMr/cGCx9up5x61la9omk6xYwrqUYCRKQhZiZbWTGCcnlkPAOeRgZPG6tRpIJI/Kmlsms5HiWAA7gJT0Vuu3J+6eMGq+r3YiETStLbXGWWC4kGdpUYZTjnOCcH60OHYrm012PMbP4a3xZm1G/s7UxYIhT948gzjJ5A9a1bjwj4Z06GVReXF7Nxgm4CkN2RRgAZH1zikawa1uQZtUt5AFG1HZ2BODnJwM8dO3Gas6bJZ2jKv2WWRlALBMFVz0xuPPc11OtNvc5FRprocrZ6daEM0haONTkZXzGbHrngfU1MdQsLSFWsBGWcfJKzgs3/AugH0rsJNAh1rVjI9rLCm4b13MXlx1ygwMY9fWtuPwvpNwU/wBCtbBFOdhjHmsQcYyThenbtitVXRk8NK+h5XbrqWrTeTp9jcX0pbBAQrGp9yep+tdBpPwz1rU3WfXNQOl26t9xMNIR6EH5Vz7561694f0vzrMx6IsMdpGfmldv3aMevTljWhcDQ9NVDJGuoXDD/WTfcB7gDoPwyaUsR2NI4SK+I5Pwd4K0Xw/prXmn2UVpCVHnX9zy5GO2eSPpgVn6146tdML2vhi1864ZsNqF2gJ4/uJ0FdZrDSalGRfs0cIG1Y1OARjoB9K4XxNH4Z0+RkXTZ5bhh+6gGXBPvjoKzjLmfvGk1yR93Q5PxJruoXUmbu6kuppTvaSRycduB0rnZprma7NtbhjIq72kc4Xnjk44rU1qPF7vv4Y7VpCPJtbdSrnjuvX+gptjZXVzlXhVYVb/AFUbZGP7zv8A0FdUUefNtsrafC0cPyrHIwY73A4z15J7Vait5Hbcp+dv+WrDp/uj+pqeZre3wZGDhc7FQfIvPoO/TrVO4uJrg7ED/e+4nLE1RBJCbWw8xLRTLcNnzJG529+vp7CsPU72W5n8qGUEMdjsDlmz0VR05P8A9ety10S5vFCusmxulqj4Lk/3mzzn0HGM1ora6bo6i5ltz9piQxPalN8Yyv3iAMg5IHPXHAqXI0jTb3OZt9LntUiN75cEchISF+JHI7D36k9gB+NaUkcOoRLDFEyxPtKxzrtXbnqQOABj15pmuais/wBmYN5ksaCNJZWKebuB3Rk9wccAcgDmuT1PxFaJZtdxwTX19M+xJjuEfIAO1OoQgD5iOQpOBUtsuMYo6nxFqNjoVjcRQyN5sjmS5uU42HphAehGB079uK8913Wp92+5iEUkpYxJgYU45d/VjwOh5PtVTU7mSa3N1fXFwxVmeBsDBbIAcKfoRnspGKd4N0a58T6x5NpcRtcyN5SGRiFDEfKpP8AxgL6nAGTWMqiirmii5OxU8JrZ6j4gtdLla3F3NPtMZkB8nA3b2J52jocHkkCvV9RtTpnhOL+zbP7Pd2cqpEJIQEuW2M0U74PyBumc5HT0qlr+iwN4bm0uwjtLdLNkgXV1jSSZcE+ZgqCwZXCgqeSHwQMGoPC+sXPiLRY9D1AXEesae5UvbSN+9AJ259UYE5BycE4wa4p1FPVbHVThy6F/4Y+JrjxL8MbttTQS61o6S+TcSMI1vsxuy/OvCvhWUng/KD3NaWmarPJb2NrIYZ9L1OzUMzRgpHICrl93b+IemQTXHQ6OvhvxfqGly3JXRvFGmz2MxKbYZZnhZoCjg7TluMjoRggV0HhFZZIdLa9sordYRaSzJNP5CiBoirL5TZIYSRsMcj7wJ5FOE1rYbjtfc6e5jkUx3GmmNfMv5b5A8jho5WkVHMrdlzznvgDo1dLDMZtL037RGsfkXi26SoN3zsSAVA+7u4Pp2rCttNlvNWjSRb63W5ebdvUeU6kiRH3DrGVIA2jPAzzWzaaXO1tFc20U9jM6EMks3MIL7d0nQOAp+VhgrwO1Xq7hY7DSRtV7QW6pDdRCPYq7BGRg5AHC4IBrL8SpLPJFP5bpPfmKPMB/1aE4Z3LDCkfOuQTuBHINbWlzLLfWZtyssVxE0HmBwygjK7HzyfUE8k5FJbi3k+H4t9Ri/wBG+0TWtzkFzEm4kHHOcNhqUvisax+E5jVI7Np4rptOV7hojDMZIiks6Y2FC5I+YqvylgenG04NS6r9kl0OSA3e2KKNUaa5TkjAwzqOSHGOevfrUrQSTaCHhgY3ts7qY5XB3vG2AXJJHIww5wR+lPUYGu9PF5ZfZbicMkc6yLzIijBzzyF5245Ge4FVsyGQWdy2mxLcLZK9ldoj3aREbgm7Zu9/LwpJ6sDnqCTLfBNV3Wwe0lsy0jT+fw+1gw3RseMqwOc9RnpgGo9LRrq61Sx1GVvs+7hHl6jaweWM8ZXDKHHQEHpVPw1HanS72y1byp/NJEUMTBX+U5XygT95cbwB1A6YptN7E3Rzmm3UFnos0X+kRXW9gJYB5nJzjDHlcjnv1HpWHqWt3+mTWuj28001zccwady0kkZxv3SdQm0cyE+uOcCus0mz8Q6pcWkiaVZw2gTaykbirEcAs3PHH8j0rt/DeheH9Oha6utItb7WHTE08uREgPJBxjzCD9FHTFSHL2OH0u38W6ncRQafbSRzrGIJru0hLGGLPEZlY8IB1J7DPWux8P8AhLS7HUrc3iTaorQbpw0oEMcgP8TffYNngIACBye1a6yXXkxwz3gaNSSsUUQjjBx/dXtx3yake6S3tTI7xooG4ySHnjqT+FFi7WH+KNfisLS30+1tF3SApbWdsm1FGOWIHQdPcmqWivOLWOe/JuLiFdzOi5yepVF9BnHvXJWOtXfiLxUy6TFDFZ22VaW5Us0zHoTgjCng+vNb/wBgu2vNP1C51KSA2KOrWNsVW0mkIKiT5svwCcDPXkirsTzXdybVNVu4W+0fYJpvkO2NsKF9zn19K5z/AIrrxJIxtoV0mF+WkYgMff8AvHj6CujuNQsIPnd/PkGcKWxH/iay9U8Qz3JEccvkoOix9T36Y5rSOnQznruzOh8H6BoUEt5qt7JqV0SGkYkhZCf7x+83bjpUGsaPqt9J5O+2tbcfdgt/mGPwwMVPc6jDGqXAm2xgbzIA3mlg3QDgA89/UVz1x4llu3e1tZ8ocMWjJY4P90nG3oOO/NaRlJmMowSJJNP0TTrlk3DULwjiJ5NsUZ6DdjoP9nqar3emxvbyXF4d0CoUQZ8vCt94IF5TBzg5zSW+LOFftBSN1BXaq43EnJJ9ST/Ks3XtYKKjrH5m6RQQ3IA7t7fXtWnK+pg5RWyLs+pzWLLa6UyRK/zwylB9pAxgZHt0LDt0ANc7qepRWcUSot1crHKz+W1wC5IBO5mc8YPc9M1FeXlzNmQo2+VsKduFXjOeT7DHToa5TxPrOm6crN5qzXsrMrI8QLSFmGZGGMopOfl6Z57mndImzkX9c1ZYrcX32i3mvP8AljBENycjAI9WXJG7jucdq5hlmklkubohpr1wPJh4aXkfKp6gdCRxyeeKp3etPbzC7vfMkvJWBtrNUG856Hbyck8e5PQVDZ6fr82rSvc2Ujy+Xvmt4QHSzh6/Pz8x65UHjHOelYTk7X2RtGPY6Cw0O/1/VDHpq7mKOlrCuN7un3kjU/gM9BycjgV3PiLwRN4U8NTSaduvPJtFe4EEoSTyJF5lB53ojhTzyCFOQTWBaXusada2/ie21eJdYhnWGGR4hHMsLhlIKheFDc/NkYOCKksr+PUtHgvYdK+zXULfam2SSxQAhvLYIoyCrOsZKNgEHgZUE+bUqSfodsIxXqVF8XeItC8VWv8Awk9hZTT6k6hmtdhfUH2hBIgU4LMCVZwMksf4hXa2ukWljcSapZX8cxkuRc2trGxSSOfcN0GMfNIURsk9CN3AJrJvodIvluLrSTH9s3rNJLLLGssUbBWkt4FOGbEhVht5JUH1q5J4i8rT/wC39G1CO61NWZNS0qG2QxyxElZJYo8ERsFJYE8Hc69sVz1Jp25VbubxjZu7uQftBW8L+H5Us0RtLt2W6mdLZImtlldhGUVTyiyZU7flGSDyRSfBfUrrUvCl7frLdXF5b3tpDIkiCYxKoZiVDffDKASOCMdQBXO+NtF1Dwfbw3+g6nHd+FPEEbS6ZcIoKXSNgPbS9dkuSMp0JXI6VkeC9SudK0m+s4JltQ0cdxIChbypBPtjkQjlXAyD68DPNdNFe6Y1Je9c+ipNYsrLWLe0WadJ4rtXLOzeURkp5hz2Ylc7MgAcYAzWzprSzyQ2guIZLeeIhQsYeK5DRk5B/hBJyCeteTeJvGt6ni7TNGjaIxSWyhrW6KK9o/mL5c+4ZKLw425OcjPGca2la7/acsNrEkdzb3mo2sE9kYTbyW9nIjF/LKHJI2h/vYUHqR07EjLmPQ9Gvp5bKwvEthDHIolMMnHk/wAAUkfe+ZepycGuounngW4i0xGWS6kN3biQ/KGHMgGevGePqa8fum13TPDH2ZZ4r7XrSWa7eOKF44rmFpT82WOFKqwY8/wHgg12HhnWrjUPBul6lp66lqV3ZR+deC5lWK4kQMys+xuGzjgjAwcjjIqZqzTNack00dLZ/Z5NOiuZYkjlldvN3HaSy8AH+9gcc+1ZWrRw2G8Q38cCxxeXvueYzIWG2SRhghvurxgEYPaud8fXHiOz8NrJDNb30UkgmkmSTa6SFgEeU/dWIx5DADJdeOxridUl18aLFDeaw01pdzrp10t2A8l/G6sd8snSNw210VgGJUryCKlBKR3EbsuvNNFaNaX0cRSSWSEf6TlfljQMcH7vOCAwA6msTXPEXh9Zre+07zZJ3czW98F820hUgKse9OqI67DjlCSOQDViR9aktWiuHluPseHs4raNW84eUBIswHKqJW4kQ8joBUnhSWxNtNos+h2dis0C308Lj5J5Xb964z1xLhScA7sHHNWrmbZjN8S9BtpoEvbyGzs7iVStxBdrM0ijICS4DHJxkjqB161rP8YvAEcbh9TuriS3BOYrCQqTnhkx74GSa+XNH0LVoriMmOxt45ASTcMCm36DOG9sdfpWlb6KkdpbyT+IYLRR8+2Z2GxccLkjGc55OAe3rVujbS9zP277H09o/jHw94hvpl0DUg1+2yOB5GUx7TgsihmHzKSMgjqT6Vfvgt+fPv5XjTeflUnCj27YGK+Y7C+8PadZyXb6vbzNI5dZCS5GB0BTkse+etah+JOk2FtHCHuWZo/liM5VeBkFiTkHP/189KqNJkuvc99TWrKxi8q1ycFvMMUYUuSf42H4Vl3XiKSdfOaaJFkwAQdxx/iea8Mj+K+q3c6w2cNkZIxy6szsc4z8oABJGBWhL4j1+a3Eotre1ZiMSyktv7q2Cew/QVTSi7MXtG1oepX2s2VvIwluTIyDcEB8tfUAt15xx61nah4tWV449OshOyvuRgp8nI5wMnlgc8/hXjmpahr0WrLf3V9dNsYOlqBm2mH93B559c5610OgeMbnUJLK0iis4bhQ5vEuCFUSfwrCeMED165x6U7xIbn0O1aC91CYSapKzAcokeEHTlVUdO+asXE8Fhb4iRLKDGWfhRuJ4yx6n0ArOuL+WBWuWeSKZoQz2qqTJEh4XpwMkdc9MVBD9suVLXkW5zIXSF8yxxr/AAlsDg9eRWnMjLldy1fXzmMSQxgKSDvc/OcdcA8A/Wsidg905luPOfaZZFY7Yo0VupbpuGRkZz6Zo1SXTdPX7XruqWDtFEHhw3lh2zziPJ3t0+7nj61z13pvi3xCFezs49D0MASi/wBbbyFkC87xEPnfHXGOgGaiVVLqXGl5EPi7xIjM1vpnlzNggXTIep44B6A9Ocn061gadZXE9zMumWyXWobf395cS4htl67mJ6OecKCScfhWp8P/AAtY6vrHmjVLu8sEmaBruaUQpdy43MsCr94FQD8xyB710N1axx6HJ/ZcZ8m3ZhLaWlo8ckCkjyn8tskHI6ncD1yKwlWSfc2jTdjO8P6V4d8OabLq2o6lPPq08WRdkbSqsSN6E/6vIBwfv/TrVLU9WtbPUDfWUzyLbXGIvMhwzxuNpeQg/McblBXpg854rkNevry8ufKnnJWFAqh/lP3jwVHBOSefrVY2l4jeW9tcyJHgBljZlXdyNpHGD1HY1p7Lm1k9SOe2iWh2l7rkK20PkCeP7Oz24gicE+SwwMN3OBkEknJwelbnwtv7KfVm0eS5EiXcSIJChjLKvQ/7+PX+4cda8xst000MKxuqhtilFY5yehPc5z9PwrW0H+3dC1i11W2sb1ntLgSKfIco209mxgjAxntXPVwys1fU2p1XdaaHsvibRLjUtDlUS23mabG0eoIYXMrb2XyyFHQFfLVAAQM8nkGuD8KW8uneMobSWRY7mynkilttzKsiE4dHB5b5clTkjgnrmuv0vxNdXd1NLf6Nc3cM0Diwy7W48tx+8bLfdcK0igYPQYI4xV+KXhmw1DT4dZtpwkkCItxfTyozygp9xwSC2cK27uWYYrzoO3uSdrnZKN/ej0L+gxyWkOoeCYY2W01W6nvtNuQyqLVCMpOEbKt5cm5XB5XIPGePNdMjSbVNQ07WGjma2d5ftBDR/vVYb0dV5Kvjrnggc1vfD/xLdWsqadqixyLDuig3SoCiuuyTaxPXZk/7QG0+tZG2BvE6ylF+yXtt9mvWtnUNyNhdFLcggI2ORmuih7kmpGNRqUVY7KS6bWY21O32jULi3u2mgvbYB4mglV47YjIIG3vknAIJ5rT8M2lrBfWa2MO1byawujDCHeKISg7JGZsFuRyMgkYGMbs4Xhq/2W95DNtaPUIvKaG6j87fG7lZS75DLKcR5IJGM4ziuvs7rSbfxRbaw2pyNbWyywKvlOzQyu6BY2AHMaYBBHGckY5rrjKPcxsyzoOoatp97d+HdQeC40nS5IUlurqY/wClQ3CMS7vwofeVwDwqnGSDiu48M63af2oLyKGWOHT4/JuWlhEcFxE67WhKvggDAbHQHAz1FeZy6bp8banZ+IPLuLSIzzrNaCUPLvYqIPKwS5QBHUjjgkDpXTfbtD1ltHjvrrzp7vbp7WyTvJatcRHzAsqkcksCAz4BBGecVTlF9Rx5kdZqbx2XgKaysp4o9Q0Z0tlYRuwu0ZWZUVOrrIp2qT6nB4FcPpsyDV0nh0+xbT9culj2fcxGsStaL8xO2VWVsEcnaM8V1Nnf6bq9uyQarBcafqqtYXxjv/Lmsech4255UHgAjbtzz0rz/Wo/K1CfToVa31aS/ljuLeSFEiNzGFY3KyglEkdVRlkcbWJYHaazX5Fy7mm2sahcQzXD3N5DfW00OoC1S02i0VXEbqZB99XXBXvnPbgV4/EaxXlvqht7dru1vJIYoYyxe5DoWnVmYbUZlCttP8Ue087Sc61u5T4iUwSXE39l3ixXMkgHl7JIiHnhQZOMurBTkA5A4qzNpiQ6bd2XmRXFnNbi4ub+0RV86cOA0hQcBWDNlRzn6VV2ZnzzYvLHdGe3lmWZv4ITgDI5Jx7VahjZmzfOzpOykvPLvY47qp64GQM0yOf7LqUym3t45Y22J5Db4QyjbuJH3gTnp6+lLcXF5cYnuo7SGTzRkS/MZhnnO37owMep9q7ZXbOS6sWrTLq1rp8Ut1Kv7/7EkY2SYBPmMAQDtAzt9qYujvf28N9HPYgXNz5CJcMFYvtBJLYwBk45x7cVpt4dtrrQVFoT58cXnuY0O5lcjKsuMgKMKP4e5Jp2k+DNen8SnT9IvdPUTXAYB7hcEAYD7ScJgHGCc+lZe0px15rF8k5aKJi3EFzYXUojSKNYJB8xx+8P+wB1xyevT61uaL4pt44JINQ+2XaPgmaAqhhUkjYqt1z8pLHByMDiuq8SeGvCegRSRa7r15f3E1uhjstOUiLeCR++kILJjGQu0EfQikeT4X2VzCYvAL3Fv5PmJ/bGpyNljjnYjY59G5rneMpW+Fv0/wCDY3WHn3S/ryObfxZoUkyx3cU8x27GlknjVV6AE5zzhRWha2ukaxGklmF1DeSkcFvpkk8wYjOAiqSeoyScZ71NH4yNtNIPD3hTwxo8OSw8jTI5GXA67pAxJ/lXQab8SNeu9FifVviBqWmw+cwEOmxBbt12/I4VQFYBuMMVGOeazniGtofj/kONBPeRB4e+Fnjqfbc6f4av9PhjjAifVpxa+Z6lo8liPwrpv+Eb1PSI7keL/Fb3cUiru0qzkSGFDnAAkkbzM+pwM1wXiT4ia/rbTQ/bpIY1k3JM8rNcS44Vi/QccHaAPr1rlNSuJbjzJ3+X5RuVRgOOhY5JJb1/OpTqzdnoW1TjqtTtrzxdb6Hfm50tfC0MjSNEl5DBJqFzEByMvIAf++cDNVNS+JGuyXjz2GsahcK4+drq3gAkHcBcEIDkj1P4V5xeOEYso2jGAQvX86q6nfTJDHEV5xkMTkkdv5V1wwKlbr6nPPFOCfQ9Ws/GvitbVI9Ujkhson82322yfuwQRlSAAoAH3Tyce9dNpGpeGzZhrW5nkuk3iJJbJYzJbFcIsj7gCFkP3STu6DGM14BbeINagvPtUepXHm7QrFm3K64xtZTwRjsRW3HPe3dpDqrxShLgndJs2pvU4IXHC+3SorZfKFtUkFLGKeyuz0W8+1aHarqMWtxx+VGHuLjTtL/49zIwzhmUttzkZ5AOPeuD8RX2oyTSJbeJNRure3mV7YrKyK4I3ZIXADe/HQ1ueEfE95pVtKcx3dreQfY7mzuj5nmxHO5SCcL1yMdwKr3Gk6Xf3TWukK89nCvE80nkyKpUsEwvWQYOT0+X0Oaxov2Unzr8jWoueK5SjfX2o3AWdtRunYrlhIxHXkjI75POPf1pkep6pP8AI2q6hKhJHlG6kCknA4BPQ8+/rUK3DRtC8pZ5IgBsYfK34ew9ePSoJkWSQMpVSeVLnocc8dq3jFPRohyd9zr/AAPPIl3Np0kS3yTKskfmfPIChA+UHnIOAVzyOa9NtLeytIZrYaPY38cts0slvJGyhh3SNwMHaxBwASpGQea8OsbyFlDyq0cu4GKQOduf559/zr1DwX4lkktS2rtFLNpsLy2sr8PFk4faR94bcHA6YNeZiqTjK52UKiasec+JCPPjuhbxwXUIMbhCBtYdVGOg64J5IJqjDdTXF1vsIxFJtKlj8zKpABUk9QOxxxn8afq88LXTSQBRDIxZhGxKliT2PI6/171Qk3296slvOR5bAo6n7p/+scflXp0oe5Z7/wBaHHOXvaHfwy2898skMUi28yxXqt87LaNESkkRb/loSv8AdPUHrmvSdPNtpevtpNtHfeVeanLcw39uoliDN8z28xbOwjLjb/dHBryfw7epew21rELq0ubZGCiKbfHcJMvzyyg8A785XjKuccgA+jaDdvJorROZo5bS+jiu7YutwFztClT1VCq7CeSu0HqKWzsVe+pc1K0aLXpr2XUG063njSG1vbeWR7gSFDGAingOMdCCNvQg10ljaWmpXSztEt3bTWygTxhhFcoSNwOD/rNyqynGAM1m6paavcNfCG8SYnEmnwSp5f2aQLtYecPmCsCT0yD3q81oEiSXT3Imt7Y2375iRNHkMysBj5jz84wQST7VTjF7oE2jpLGSC3jLpYwrE10iERRKV+YYy46nkj3rLurSz/tJtVuNMiuriBSWvEVGF5Gc74Qo9CoAz3wKtafdrBNDKiOpfZiMncflwQCe+MCptYe1fV7t7GS3KtOXlijAGyRhmRHHZg3PvuFZezjzbGvO3Hc88utBubLR4NXvfD2k6hqtqTbma1VoZvs0mNpkUYAdVYhl5HFLdeH1uPDy2mm2Edp5hli8yO4dFuIeD8qA52k5U981veImTT9OFyGmkW1tJIikszkzLwxVmXJLAA84zjIzWBostq+sQz8wiOEC2vHbaHLhRsKdAdpQBictt555p8iTRHMz/9k=' alt="" title="Click here to edit profile settings." />
                            </a>
                        </div>
                        <div class="userinfo">
                            <div class="info level username">
                                V39F8VF
                            </div>
                            <div class="info level nickname">
<p>Sub-Acc V39F8VFSUB09</p><p>V39F8VFS09</p>                            </div>
                            <div class="info">OTP: Disabled</div>
                        </div>
                    </li>
                    <li class="visible-mobile dropdown-submenu language"><a href="javascript:;" data-target="#" class="dropdown-toggle withripple language-selector-container" data-toggle="dropdown">
    <span class="icon icon-flag language-selector langFlag-en-US">
    </span>
    <span class="language-text language-selector">
    </span>
</a>
<ul class="dropdown-menu list-language" id="language" data-currentlanguage="en-US">
        <li class="en-US"><a class="changelanguage-link" data-value="en-US"><span class="icon-flag langFlag-en-us"></span>English</a></li>
        <li class="zh-TW"><a class="changelanguage-link" data-value="zh-TW"><span class="icon-flag langFlag-zh-tw"></span>繁體中文</a></li>
        <li class="zh-CN"><a class="changelanguage-link" data-value="zh-CN"><span class="icon-flag langFlag-zh-cn"></span>简体中文</a></li>
        <li class="ja-JP"><a class="changelanguage-link" data-value="ja-JP"><span class="icon-flag langFlag-ja-jp"></span>日本語</a></li>
        <li class="th-TH"><a class="changelanguage-link" data-value="th-TH"><span class="icon-flag langFlag-th-th"></span>ภาษาไทย</a></li>
        <li class="ko-KR"><a class="changelanguage-link" data-value="ko-KR"><span class="icon-flag langFlag-ko-kr"></span>한국어</a></li>
        <li class="vi-VN"><a class="changelanguage-link" data-value="vi-VN"><span class="icon-flag langFlag-vi-vn"></span>Tiếng Việt</a></li>
</ul></li>
                    <li><a href="/site-accountinfo/ProfilePicture" target="main"><span class="icon icon-account-circle"></span>Profile Settings</a></li>
                    <li><a href="/site-main/Password/ChangePassword" target="main"><span class="icon icon-lock"></span>Password</a></li>
                        <li><a href="/site-main/SecurityCode/ChangeUserOwnSecurityCode" target="main"><span class="icon icon-sercuritycode"></span>Security Code</a></li>
                    <li><a href="/site-main/otp/SetUpOtp" target="main"><span class="icon icon-otp"></span>OTP</a></li>
                                            <li><a href="/site-main/ProtectionCode/Setup" target="main"><span class="icon icon-key"></span>Protection Code</a></li>
                    <li class="bg-light">
                        <ul class="list-unstyled">

                                                        <li class="visible-mobile"><a class="link-logout"><span class="icon icon-logout"></span>Log out</a></li>
                        </ul>
                    </li>
                </ul>
            </li>
        <li class="hidden-mobile logout"><a class="icon icon-logout withripple" data-toggle="tooltip" data-placement="bottom" title="Log out"></a></li>
    </ul>
</section>
            <section class="header-msg" id="headerMessage">
        <span class="icon icon-home withripple" id="home-icon"></span>
    <div id="marqueeMessage">
        <span id="scroller">          
            <span id="public-message" class="maquee live-message"></span>
            <span id="private-message" class="maquee live-message"></span>
        </span>
    </div>
</section>
        </header>
        <main class="content" id="content" data-default-url="/site-main/Dashboard/Index">
        </main>
        <div class="float-section">
            <div class="progress-box hide" id="progress-box" data-toggle="modal">
                <span class="icon-progress"></span>
                <span class="txt-progress">Data processing is in progress.</span>
            </div>
        </div>
        <div class="div-feedback en-US hide" id="feedback-function">
            <div class="feedback-box">
                <div class="icon-feedback"></div>
                <div class="txt-feedback"></div>
            </div>
            <div class="icon-close-feedback" title="Close"></div>
        </div>
        
    </div>
    <input id="oldMainRootPath" name="oldMainRootPath" type="hidden" value="/ex-main/" />
<input data-val="true" data-val-number="The field OnUserId must be a number." data-val-required="The OnUserId field is required." id="onUserId" name="onUserId" type="hidden" value="31262672" />
<input id="mainRootPath" name="mainRootPath" type="hidden" value="/site-main/" />
<input id="passwordHash" name="passwordHash" type="hidden" value="asg1" />
<input id="howToUseRootPath" name="howToUseRootPath" type="hidden" value="/site-howtouse/" />
<input id="memberInfoRootPath" name="memberInfoRootPath" type="hidden" value="/site-memberinfo/" />
<input id="accountInfoRootPath" name="accountInfoRootPath" type="hidden" value="/site-accountinfo/" />
<input id="subPageAccess" name="subPageAccess" type="hidden" value="[A][B][C][D][E][G][H][L]" />
<input data-val="true" data-val-required="The IsInternalWebVPN field is required." id="isInternalWebVPN" name="isInternalWebVPN" type="hidden" value="False" />
<input data-val="true" data-val-required="The IsShowIntroduction field is required." id="isShowIntroduction" name="isShowIntroduction" type="hidden" value="True" />
<input id="userLevel" name="userLevel" type="hidden" value="master" />
<input data-val="true" data-val-required="The IsSubAccount field is required." id="isSubAccount" name="isSubAccount" type="hidden" value="True" />
<input id="subUserId" name="subUserId" type="hidden" value="1914097" />
<input id="userId" name="userId" type="hidden" value="95009000" />
<input data-val="true" data-val-required="The IsEnabledOtp field is required." id="isEnabledOtp" name="isEnabledOtp" type="hidden" value="False" />
<input id="messageRootPath" name="messageRootPath" type="hidden" value="/site-messages/" />
<input id="exTotalBetsForecastRootPath" name="exTotalBetsForecastRootPath" type="hidden" value="/ex-totalbetsforecast/" />
<input data-val="true" data-val-required="The IsInternal field is required." id="isInternal" name="isInternal" type="hidden" value="0" />
<input data-val="true" data-val-required="The RequiredNetworkSpeedCalculation field is required." id="requiredNetworkSpeedCalculation" name="requiredNetworkSpeedCalculation" type="hidden" value="0" />
<input data-val="true" data-val-required="The DisableMessages field is required." id="disableMessages" name="disableMessages" type="hidden" value="0" />
<input data-val="true" data-val-required="The ShowOldCustomerList field is required." id="showOldCustomerList" name="showOldCustomerList" type="hidden" value="1" />
<input data-val="true" data-val-number="The field UMAnnouncementPopupClientIntervalInMinutes must be a number." data-val-required="The UMAnnouncementPopupClientIntervalInMinutes field is required." id="UMAnnouncementPopupClientIntervalInMinutes" name="UMAnnouncementPopupClientIntervalInMinutes" type="hidden" value="60" />
<input id="reportDomain" name="reportDomain" type="hidden" value="/site-reports" />
<input data-val="true" data-val-required="The IsDarkMode field is required." id="isDarkMode" name="isDarkMode" type="hidden" value="false" />
<input data-val="true" data-val-number="The field RecheckinIntervalMiliseconds must be a number." data-val-required="The RecheckinIntervalMiliseconds field is required." id="RecheckinIntervalMiliseconds" name="RecheckinIntervalMiliseconds" type="hidden" value="30000" />
<input id="SessionId" name="SessionId" type="hidden" value="4irji14hwwd40dxxnjralnua" />
<input id="resultRootPath" name="resultRootPath" type="hidden" value="site-results/" />
<input id="transferRootPath" name="transferRootPath" type="hidden" value="/site-transfer/" />
<input id="assetAppPath" name="assetAppPath" type="hidden" value="https://stcdn.b8ag.com" /><input data-val="true" data-val-number="The field CDNReCheckinIntervalInSeconds must be a number." data-val-required="The CDNReCheckinIntervalInSeconds field is required." id="CDNReCheckinIntervalInSeconds" name="CDNReCheckinIntervalInSeconds" type="hidden" value="60" /><input id="betlistDomain" name="betlistDomain" type="hidden" value="/site-betlists" />
<input data-val="true" data-val-number="The field CustId must be a number." data-val-required="The CustId field is required." id="CustId" name="CustId" type="hidden" value="95009000" />
<input data-val="true" data-val-number="The field SubAccId must be a number." data-val-required="The SubAccId field is required." id="SubAccId" name="SubAccId" type="hidden" value="1914097" />
<input id="SessionExpired" name="SessionExpired" type="hidden" value="Your login has timed out." />
<input id="Here" name="Here" type="hidden" value="Here" />
<input id="minAgo" name="minAgo" type="hidden" value="1 min ago" />
<input id="minsAgo" name="minsAgo" type="hidden" value="mins ago" />
<input id="hoursAgo" name="hoursAgo" type="hidden" value="hour(s) ago" />
<input id="daysAgo" name="daysAgo" type="hidden" value="day(s) ago" />
<input id="langKey" name="langKey" type="hidden" value="e" />


    <div id="announcement-modal" class="modal fade announcement-modal visible-mobile" role="dialog" aria-labelledby="myModalLabel">
    <div class="modal-dialog ex-modal">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"></span></button>
                <h4 class="modal-title" id="result-detailt-title"><span class="icon icon-announcements"></span>Announcement!</h4>
            </div>
            <div class="modal-body" id="announcementModalBody">
                <iframe frameborder="0" allowtransparency="true" marginheight="0" marginwidth="0" scrolling="no" id="annoucement-iframe"></iframe>
            </div>
        </div>
    </div>
</div>
<input id="no-info" name="no-info" type="hidden" value="No information is available" />

    <div class="modal fade" id="data-processing-popup" role="dialog" aria-labelledby="myModalLabel">
    <div class="modal-dialog modal-float modal-progress" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"></span></button>
                <h4 class="modal-title" id="myModalLabel"><span class="icon-progress"></span>Data Processing Notification</h4>
            </div>
            <div class="modal-body"></div>
        </div>
    </div>
</div>

    <div class="modal fade um-message-popup" role="dialog" aria-labelledby="um-message-popup-label" id="um-message-popup">
    <div class="modal-dialog modal-float modal-maintenance" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"></span></button>
                <h4 class="modal-title" id="um-message-popup-label"><span class="icon-under-maintenance"></span>Maintenance Notice</h4>
            </div>
            <div class="modal-body">
                <p> Dear valued customers,</p>
                <div>There&#39;s a planned maintenance (GMT +8) and during this period, these features are unavailable:</div>
                <ul id="um-message-popup-body"></ul>
                <div>We are sorry for any inconvenience caused.</div>
            </div>
            <div class="modal-footer">
                <label><input type="checkbox" id="chb-um" />Do not show again</label>
            </div>
        </div>
    </div>
</div>

    <div id="advertisement-modal" class="modal fade advertisement-modal" tabindex="-1" role="dialog">
    <div class="modal-dialog" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="icon icon-close close" data-dismiss="modal" aria-label="Close"></button>
                <h4 class="modal-title"><b>Easily</b> monitor your win loss using <b>My Thresholds</b></h4>
            </div>
            <div class="modal-body" id="advertisement-modal-body"></div>
        </div>
    </div>
</div>

    <script src="https://stcdn.b8ag.com/bundles/common/common.min.js?v=20240124" type="text/javascript"></script>
    <script src="https://stcdn.b8ag.com/bundles/site-main/default.min.js?v=1.0.8824.16260.20231219" type="text/javascript"></script>
    <script src="/site-main/assets/bundles/default-index.min.js?v=1.0.8824.16260.20231219" type="text/javascript"></script>
    </body>
</html>
