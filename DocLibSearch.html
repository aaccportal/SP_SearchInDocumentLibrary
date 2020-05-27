<link href="/_layouts/15/MyPortal/css/bootstrap.min.css" rel="stylesheet" />
<script src="/_layouts/15/MyPortal/js/jquery.min.js"></script>
<script src="/_layouts/15/MyPortal/js/bootstrap.min.js"></script>
<style>
    .nvg-input-search {
        margin-left: 20px;
        margin-right: 20px;
        width: 50%
    }

    .nvg-tr-hover {
        margin: auto;
    }

    .nvg-tr-hover:hover {
        background-color: #f8f5f5;
    }
</style>
<script>
 var siteUrl = 'spp.nvg.ru/marketing/';
    var listName = "Маркетинговые материалы";
   
document.addEventListener("DOMContentLoaded", ready);
function ready() {
    console.log('start');
            searchLoad();
            console.log('end');
  }
  function searchLoad() {
        var url = "http://spp.nvg.ru/marketing/_api/web/lists/GetByTitle('" + listName + "')/Items?$top=5&$select=FileDirRef,FileLeafRef,ID,DocumentType,*&$expand=File";
        var urlParam = "";
      
        var html = "";
        $.getJSON(url, function (data) {
            console.log(data);
           var resulttbl = "<table>";
            $.each(data.value, function (index, value) {
                    var strFileLeafRef = value.FileLeafRef;
                 //   if (value.File.UniqueId != null){
                        resulttbl = resulttbl + "<tr><td>"+strFileLeafRef+"</td></tr>";
                //    }                   
                   
            });
            console.log("resulttbl");
            console.log(resulttbl);
            resulttbl = resulttbl + "  </table>";
            document.getElementById("tbl").innerHTML = resulttbl;
        });
        $.ajaxSetup({
            async: false
        });

        return html;
    }

    function searchTextFromList() {
        var controlSearch = document.getElementById('InputSearch').value;
        console.log(controlSearch);
        if (controlSearch.length > 2) {
            searchInDocLib(controlSearch);
        }
        else {
            document.getElementById("tbl").innerHTML = "";
        }
        var controlResultSearch = document.getElementById('resultSearch');
        controlResultSearch.innerHTML = '<hr />  Поиск ' + controlSearch + ' в списке "' + listName + '".';

    }


    function searchInDocLib(text) {
        var textEncoded = encodeURI(text);
       // var url = "http://spp.nvg.ru/marketing/_api/web/lists/GetByTitle('"+listName+"')/Items?$select=*&$filter=substringof(%271738%27,%20ID)&$expand=File";

        //var url = "http://spp.nvg.ru/marketing/_api/web/lists/GetByTitle('%D0%9B%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE-%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B5%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B%E2%80%8B')/Items?$select=ID,Title,LNDCode&$filter=substringof(%27"+textEncoded+"%27,%20Title)%20or%20substringof(%27"+textEncoded+"%27,%20LNDCode)%20or%20substringof(%27"+textEncoded+"%27,%20OData__x0422__x0438__x043f__x0020__x041d__x041c__x0414_)%20or%20substringof(%27"+textEncoded+"%27,%20OData__x0424__x041d__x0414_)&$orderby=ID desc&$expand=Folder,File";
        //var url = "http://spp.nvg.ru/marketing/_api/web/lists/GetByTitle('"+listName+"')/Items?$select=*&$expand=Folder,File";
        var url = "http://spp.nvg.ru/marketing/_api/web/lists/GetByTitle('" + listName + "')/Items?$top=5&$select=FileDirRef,FileLeafRef,ID,DocumentType,*&$filter=substringof('" + text + "',FileLeafRef)&$expand=File";
        var urlParam = "";
        //&$expand=FieldValuesAsText&$filter=substringof(%27"+text+"%27,%20FileLeafRef)&$expand=File";

        var html = "";
        $.getJSON(url, function (data) {
            console.log(data);

            var resulttbl = "<table>";
            $.each(data.value, function (index, value) {
                    var strFileLeafRef = value.FileLeafRef;
                    var strUniqueId;
                    if (value.File.UniqueId != null){
                        strUniqueId = value.File.UniqueId;
                       // var strFrame = "<iframe src='http://spp.nvg.ru/marketing/_layouts/15/WopiFrame.aspx?sourcedoc={"+strUniqueId+"}&action=embedview' height='252px' frameborder='0'>Это внедренный файл <a target='_blank' href='https://office.com'>Microsoft Office</a> на платформе <a target='_blank' href='https://office.com/webapps'>Office Online</a>.</iframe>";
                      //  resulttbl = resulttbl + "<tr><td>"+strFileLeafRef+"</td></tr><tr><td>"+strFrame+"</td></tr>";
                     //   var strFrame = "<iframe src='http://spp.nvg.ru/marketing/_layouts/15/WopiFrame.aspx?sourcedoc={"+strUniqueId+"}&action=embedview' height='252px' frameborder='0'>Это внедренный файл <a target='_blank' href='https://office.com'>Microsoft Office</a> на платформе <a target='_blank' href='https://office.com/webapps'>Office Online</a>.</iframe>";
                        resulttbl = resulttbl + "<tr><td>"+strFileLeafRef+"</td></tr>";
                    }
                   
                   //     var resDesc = result.OData__x0421__x0435__x0440__x0442__x04;
                      //  html += "<img src='http://spp.nvg.ru/SiteAssets/fileIcon.png'  width='20' height='25' align='middle'/>&nbsp&nbsp<a style='color: red;  font-size: 15px; line-height: 25px;' href='" + string + "'>" + string + "&nbsp&nbsp&nbsp&nbsp&nbsp" + string + "</a><br>";
                    
            });
           
            resulttbl = resulttbl + "  </table>";
            resulttbl = resulttbl.replace(/text/i, 'ssssss');
            console.log(text);
            console.log(resulttbl);
            document.getElementById("tbl").innerHTML = resulttbl;

        });
        $.ajaxSetup({
            async: true
        });

        return html;
    }

   
 

</script>

<div>
  
    <div class="form-group">
        <label for="InputSearch" style="margin-left: 20px; margin-right: 20px;">Введите текст для поиска</label>
        <input type="text" class="form-control nvg-input-search" onkeyup="searchTextFromList()" id="InputSearch"
            aria-describedby="emailHelp" placeholder="Введите текст для поиска">
    </div>
    <hr>

    <span id="resultSearch"></span> <span id="countResult"></span>
    <div id="tbl"></div>

</div>


