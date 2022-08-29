# Rotate_raw_data

>NOTE:

   1). There are 2 sets data: 310, and 327(date); 


   2). They used different hpx version:( after 310, hpx got updated, so 327 use the updated hpx version)

   ( for some reason,   Using the new hpx makes the performance of the original rotation better, then the performance improvement of the splitting core     becomes less obvious than before).

   3). All data are coolected on Medusa Node.

/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

>DATA: 

1. Without chunk number changing: 

   310_Data: https://github.com/hcq9102/Rotate_raw_data/tree/main/310_Data ;
   
   327_Data: https://github.com/hcq9102/Rotate_raw_data/tree/main/327_Data ;
   
            // 327_data: collect most of the data on 3.24, and correct one data on 3.27.
   
....NOTE:   If need to see the compare results, please first check thoes .pptx files in these folders. 
   
2. chunk number changed:

   310Chunk_number: https://github.com/hcq9102/Rotate_raw_data/tree/main/310Chunk_number ; // complete, with different cores(4,8,16,24,32,40)
                     
                     
   
   323_32core_Chunk: https://github.com/hcq9102/Rotate_raw_data/tree/main/323_32core_Chunk .  // only have 32core test results
                     
   
 .....NOTE: also have .pptx files present compare results.
   
