module max_led(clk,rst,led);

​        input clk;

​	input rst;

​	output [7:0] led;

​	lxs u0 (

​        .clk_clk        (clk_clk),        //     clk.clk

​        .reset_reset_n  (reset_reset_n),  //   reset.reset_n

​        .led_pio_export (led_pio_export)  // led_pio.export

​        );

endmodule