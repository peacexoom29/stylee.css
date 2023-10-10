# stylee.css

        body {
            margin: 0;
            padding: 0;
            font-family: Poppins;
            background-color: #333;
            color: #fff;
        }

        .container {
            
            display: flex;
            height: 100vh;
        }

        .left-pane {
            
            width: 260px;
            background-color: #222;
            display: flex;
            flex-direction: column;
        }
        .buttons{
            margin-bottom: 50px;
            
           
            
        }

       
        .left-pane-button {
         width: 60%;
         height:45px;
         border-radius: 6px;
         border-color: rgba(255, 255, 255, 0.2);
         border-width: 1px;
         padding: 10px;
         font-family: Poppins;
         color: white;
         background-color: rgb(34, 34, 34);
          cursor: pointer;
            
        }
        
        .left-pane-button.hide-button {
            width: 20%;
            background-color: transparent;
            border-radius: 6px;
            outline: none;
            cursor: pointer;
            margin: 10px auto;
            font-size: 20px;
            background-color: rgb(34, 34, 34);
            border-color: rgba(255, 255, 255, 0.2);
            height: 45px;
            width: 40px;
        }

        .left-pane-button.hide-button i {
            height:45px;
            padding-top: 0.1rem;
           
            
            
        }
        

        .chat-list {
            flex-grow: 1;
            overflow-y: auto;
            
        }

        .chat-item {
            font-size: 0.85rem;
            padding: 10px;
            border-bottom: 1px solid #444;
            cursor: pointer;
            
        }
       
        

        .chat-item:last-child {
            border-bottom: none;
        }

        .right-pane {
            width: 1106px;
            background-color:#fff;
            display: flex;
            flex-direction: column;
            color: #fff;
        }

        .top-buttons {
         background-color: #ccc;
         display: flex;
         justify-content: center;
         margin-left: 25rem;
         margin-right: 25rem;
         margin-top: 1rem;
         padding: 10px;
        }
        
        

        .floating-button {
            
            width: 10rem;
           height: 2.3rem;
           border: none;
            background-color:#fff;
            color: black;
            border-radius: 5%;
            cursor: pointer;
            margin: 0 10px;
            display: flex;
            justify-content: center;
             align-items: center;
             position: relative;
        }
        

        
        .chatgpt-name{
            color: rgb(217, 217, 227);
            color-scheme: light;
            display: flex;
            justify-content: center;
            font-size: 36px;
            font-weight: 600;
        }
       

        .floating-input {
           
            padding: 10px;
           background-color: #fff;
            
            margin-bottom: 0px;
            margin-left: 10rem;;
            margin-right: 10rem;;
            border-radius: 0.5rem;
           
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
           

            
        }
       .floating-button-three{
        background-color: transparent;
        color: #333;
        position: absolute;
         right: 180px; 
            
            
        
        
     }
       
       
       
       .input-box{
        background-color: transparent;
        border: none;
        width: 600px;
        outline: none;
        height: 30px;
        color: #333;
        font-size: 1rem;
        
        
       }
       
      .message-area {
            flex-grow: 1;
            padding: 20px;
            overflow-y: auto;
            color: #222;
        }
      
            #sendMessageButton {
                
                border: none;
                cursor: pointer;
               
            }
            .r-preview{
                font-size:0.7rem ;
                color:rgb(86, 88, 105);
                display: flex;
                justify-content: center;
                margin-top: 0.1rem;
                margin-bottom: 1.2rem;
            }
