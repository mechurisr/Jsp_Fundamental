<%@ page pageEncoding="utf-8" %>
<!-- ajax_proxy.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ajax Get</title>
    <script type="text/javascript" src="jquery-3.5.1.js"></script>
    <script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=c50f6c0f91e761205f077b489f5b2c52"></script>
        <!-- services와 clusterer, drawing 라이브러리 불러오기 -->
<script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=c50f6c0f91e761205f077b489f5b2c52&libraries=services,clusterer,drawing"></script>
    
    <script>
   

        $(function(){
                 $("#testClick").click(function(){
                        console.log("테스트 클릭 성공");
                    });
                 
            $('#btn').click(function(){
                    var address = encodeURIComponent('http://openapi.seoul.go.kr:8088/6c4d744372746a72313236744a785a54/json/bikeList/1/5/');
                        
                $.ajax({
                    url : 'proxy.jsp?url='+address,
                    type :'GET',
                    dataType : 'json',
                    error : function(){
                        alert('error');
                    },
                    success : function(obj){
                            var msg = "";
                            
                        /* $("#sel").append(JSON.stringify(obj)); */
                        var jsonObj = JSON.stringify(obj);
                        msg +="</tr>";
                                                msg +="</thead>";
                                                msg +="<tbody>";
                                                for(var i in obj.rentBikeStatus.row){
                      let a=obj.rentBikeStatus.row[i].stationLatitude;
                      let b=obj.rentBikeStatus.row[i].stationLongitude;
                      var name = obj.rentBikeStatus.row[i].stationName;
                      
                      var msg1= "";
                      msg1+="<body>"+"<button id="+name+">"+name+"</button>"+"</body>";
                                $("#sel").append(msg1);
                                
                      
                      msg +="<td><a href='https://map.kakao.com/link/map/"+a+","+b+"' target='_blank'>"+name+"</a></td>";
                      
                      msg += "</tr>";
                      
                      
                     
                      
                      
                      
                      
                      var container = document.getElementById('map');
                              var options = {
                                      center: new kakao.maps.LatLng(a, b),
                                      level: 3
                              };
                              
                              var coords=new daum.maps.LatLng(a,b);
                              
                               var marker = new daum.maps.Marker({
                             map:map,
                             position:coords
                     });
                               
                               
                              var map = new kakao.maps.Map(container, options);
                              
                              
                              
                              
                                                }
                                                
                                                var marker = new daum.maps.Marker({
                                             map:map,
                                             position:coords
                                     });
                      msg +="</tbody>";
                                                msg +="</table>";
                                                msg +="</div>"; 
                                                
                                                
                                                
                                                $("#sel").append(msg);
                                                
                                                
                                                
                                                
                  
                       
                        
                        
                        
                                                
                                                
                    }
                    
                    
                });

            });
        });



    </script>
</head>
<body>
    <button id="btn">가져오기</button>
    <div>
      <span id="testClick">
     test입니다.
     </span>
     </div>
   
    <div id="sel">
<div id="map" style="width:500px;height:400px;"></div>
    </div>
</body>
</html>