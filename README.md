
## Step

Ejecutar los siguientes comandos:

npm i -g tfx-cli


tfx extension create --manifest-globs vss-extension.json

--------------------------
Test event
    <script src="sdk/scripts/VSS.SDK.js"></script>
   
    <script type="text/javascript">
   VSS.init({
       usePlatformScripts:true
   });
   VSS.ready(function(){
       VSS.register(VSS.getContribution().id,function(){
            return {
                onLoaded:function(args){
                     alert(args);
                }
            }
       });
   });
   
    </script>
