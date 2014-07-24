//# LICENSE: AGPL V3, AUTHOR: TEJAS. TANK.  EMAIL: TEJAS.TANK.MCA@GMAIL.COM


var Widget = Backbone.View.extend({
    template : "",
    initialize: function(option){
       console.log("widget option data: ", option || {});
       this.render(); // render template			
    },
    render: function(){
       this.$el.append("<h1>working</h1>");
       console.log("this.el",this.el);
       console.log("this.$el",this.$el);
    },
    events: {
      "click h1": "warn",
    },
    warn: function(){
       //throw Error("Great Error Message.");
    },
    destroy: function(){
      this.el.remove();
      this.unbind();
    }
});
