# Dynamic-Tabs-Read-More-Button

   ## Dynamic Tabs
      Custom Tab Open 
      Dynamic tab makes use anywhere
      
      Example :
       <ul class="CustomTabs tabs">
           <li class="active"><a href="#configurable">Configurable</a></li>
          <li><a href="#nonconfigurable">Non Configurable</a></li>
           <li><a data-toggle="tab" href="#all">All</a></li>
       </ul>

       <div class="CustomTabContent tab-content">
           <div id="configurable" class="tab-pane active"></div>
          <div id="nonconfigurable" class="tab-pane"></div>
      </div>

      CustomTabs
      CustomTabContent
    
    

## Read More Button 
   Dynamic code use any where

      Example: 
      Just call this script in your page and pass two things: 1. TextLength, 2. Text
      function is `ReadMore(TextLength,Text)`
      <script type="text/javascript">
         document.write(ReadMore(5,"'.$nonconfigdatas->description.'"))
      </script>

      ReadMore() function
      ReadMore(TextLength,FullText)
