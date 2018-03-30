<!--
    네이버 지도 API v3가 정상적으로 동작하지 않거나, 버그를 보고하거나, 도움이 필요한 경우 아래 내용을 작성해 주세요.
-->

#### 내용 (Description)
<!--
    chrome 크롬에서 구현이되는데
     ie11 구현이안됩니다
-->

#### 환경 (Environment)
<!--
    visual studio 2008 에서 개발
-->

* window, window7 Ultimate K, ie11, 11.0.9600.18952, Device Information, etc:

#### 추가 정보 (Additional Info)
<!--
    <%@ Page Language="C#" AutoEventWireup="true" CodeFile="naver_panorama.aspx.cs" Inherits="main_multiview_map_naver" %>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
    <title>네이버로드뷰</title>
    <meta name="GENERATOR" content="Microsoft Visual Studio .NET 7.1" />
    <meta name="CODE_LANGUAGE" content="C#" />
    <meta name="vs_defaultClientScript" content="JavaScript" />
    
    <script type="text/javascript" src="https://openapi.map.naver.com/openapi/v3/maps.js?clientId=AxhGpg76LrmMsAjsQEtJ&submodules=panorama,geocoder"></script>
    
</head>
<body>
    <form id="Form1" runat="server">
    <div id="pano" style="width: 100%; height: 800px;">
    </div>
    </form>

    <script type="text/javascript">
     
            var pano = null;

            naver.maps.onJSContentLoaded = function() {
                // 아이디 혹은 지도좌표로 파노라마를 표시할 수 있습니다.
                pano = new naver.maps.Panorama("pano", {
                    // panoId: "OregDk87L7tsQ35dcpp+Mg==",
                    position: new naver.maps.LatLng(37.3599605, 127.1058814),
                    pov: {
                        pan: -135,
                        tilt: 29,
                        fov: 100
                    }
                });
            };
       
    </script>


http://localhost/gimje16/naver_panorama.aspx


</body>
</html>

-->

* Site URL, Source Code
