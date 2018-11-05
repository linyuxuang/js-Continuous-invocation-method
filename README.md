# js-Continuous-invocation-method
js  方法的连续调用



        var  long={
        	smoke:function(){
        		console.log("smoking.....");
        		return this;
        	},
        	drink:function(){
        		console.log("frinking......")
        		return this;
        	},
        	perm:function(){
        		console.log("perming....")
        			return this;
        	}
        
        }
    
     long.drink().drink().perm()
