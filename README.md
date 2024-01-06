<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Razorpay-clone</title>
    <link rel="stylesheet" href="./main.css">

    <style>
        .companieslist{
            animation: 10s infinite linear moveimage;
        }
        @keyframes moveimage {
            0%{
                top:0;
            }
            100%{
                top:-50%;
            }
        }

        .cta{
            background-size: 100% 100%;
        }
        
    </style>
   
</head>
<body>
    <!-- nav bar -->
    <nav class="bg-deepBlue w-full">
     <div class="relative w-[1080px] mx-auto flex items-center justify-between">
        <!-- now logo -->
        <a href="/" class="cursor-pointer py-7 pr-7">
            <img src="pictures/logo-dark.svg" width="125px" height="30px" alt="">
        </a>
         
        <ul class="flex gap-6">
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Payments</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Banking+</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Credit</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Payroll</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Resources</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Support</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>
          <li class="text-white relative py-7 font-mullish hover:text-lightBlue
          cursor-pointer transition-all duration-200 group hidden lg:block">
          <a href="#">Pricing</a>
          <div class="absolute bottom-0 w-full h-1 bg-lightBlue hidden group-hover:block"
          transition-all duration-200></div>
          </li>

        </ul>
        <div class="flex gap-6">
            <img src="pictures/india-flag.svg" width="28px" height="20" alt="">
            <button class="text-white py-3 px-5 font-mullish border-lightBlue
            border-2 rounded-sm text-sm font-bold" >Log In </button>
            <button class="text-lightBlue300 py-3 px-4 font-mullish border-lightBlue
            border transition-all duration-200 hover:text-lightBlue500 bg-white rounded-sm text-sm font-extrabold hidden lg:flex">Sign up -></button>
        </div>


     </div>
    </nav>

    <!-- hero section -->
    <section class="relative bg-deepBlue">
         
       <div class="w-10/12 max-w-[1080px] flex flex-col lg:flex-row justify-between items-center mx-auto">
             <!-- left part -->
          <div class="flex flex-col gap-4">
            <h1 class="text-white font-mullish font-bold text-[40px] leading-[1.2]">Power your finance, grow your buisness</h1>
            <div class="w-6 h-1 bg-greenLight"></div>
            <p class="font-mullish text-white text-[18px] leading-7 opacity-70">
                Accept payments from customers.Automate payouts to vendors &
                employees. Never run out of working capital.
            </p>
            <button class="text-white bg-lightBlue font-mullish font-bold rounded-md
             hover:bg-lightBlue500 w-5/12 py-[15px] transition-all duration-200">Sign Up Now</button>
          </div>
           <!-- right part -->
          <div>
            <img src="pictures/hero-illustration.jpg" alt="" 
            class="max-w-[680px]">
          </div>

       </div>

       <div class="absolute w-[100.05%] left-0 right-0 overflow-x-hidden" >
        <img src="pictures/hero-shape.svg" alt="" class="w-full h-full object-fill ">
       </div>

    </section>

    <!-- featue section -->
    <section class="relative mt-[190px]">

       <img src="pictures/feature-section1-dottedrows.png" alt="" loading="lazy" 
       width="233" height="167"
       class="absolute -top-[8rem] left-[10rem] inline-block -z-10">
       <img src="pictures/feature-section1-dottedrows.png" alt="" loading="lazy" 
       width="233" height="167"
       class="absolute top-[3rem] right-0 inline-block rotate-180">

       <div class="relative w-11/12 max-w-[1080px] mx-auto pt-4">

          <h2 class="font-mullish font-extrabold text-2xl leading-[1.2] text-center hidden md:block">Accept Payments with Razorpay Payment Suite</h2>
          <h2 class="font-mullish font-extrabold text-2xl leading-[1.2] text-center  md:hidden">Explore Razorpay Payment Suite</h2>
          <div class="w-6 h-1 bg-greenLight mx-auto mt-4 mb-6"></div>
          
          <div class="w-full min-h-[520px] bg-white rounded-md flex relative p-10 py-12 border">
          <!-- for left -->
          <div class="flex flex-col justify-between w-full">
            <h3 class="font-mullish font-bold text-[28px] leading-10 max-w-[500px]">Supercharge your buisness with the all-powerful
                <span class="text-lightBlue">Payment Gateway</span>
            </h3>
            
            <ol class="space-y-2 " type="1">
                <li class="font-mullish flex items-center">    
                   <span> 100+ Payment Methods</span>
                </li>
                <li class="font-mullish flex items-center">
                    <span>Industry leading success rate</span>
                </li>
                <li class="font-mullish flex items-center ">
                    <span>Superior Checkout Experience</span>
                </li>
                <li class="font-mullish flex items-center ">
                    <span>Easy to Integrate</span>
                </li>
                <li class="font-mullish flex items-center "> 
                    <span>Instant Settlements from Day 1</span>
                </li>
                <li class="font-mullish flex items-center ">
                    <span>In-depth Reporting and Sighting</span>
                </li>
            </ol>
            <!-- for button -->
            <div class="flex flex-col-reverse md:flex-row items-center space-x-4">
                <button class="text-white w-full md:w-2/12 bg-lightBlue font-mullish font-bold rounded-md
                hover:bg-lightBlue500 py-[15px] transition-all duration-200">
                    Sign Up Now</button>

                    <!-- for hyperlink -->
                <div class="flex items-center cursor-pointer group">
                    <a href="#" class="font-mullish font-bold text-lightBlue500
                    group-hover:text-grayBlue transition-all duration-200">
                        Know More ></a>
                    
                </div>
            </div>
          </div>

          <!-- for right -->
          <div>
            <img src="pictures/payment-suite.png" alt=""
            class="absolute max-w-[600px] right-0 bottom-0 hidden md:max-w-[400px] lg:max-w-[600px] md:block lg:block">
          </div>
        </div>

        <div class="w-full grid grid-rows-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mt-11">
             
            <!-- box-1 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/payment-link-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Payment Links</h3>
                <p class="font-mullish text-grayText mt-6">
                    Share payment link via SMS, Messenger, e-mail, Chatbot etc. and get paid immediately</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
                <!-- box-2 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/payment-pages-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Payment Pages</h3>
                <p class="font-mullish text-grayText mt-6">
                    Take your store online instantly with zero coding</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
                       <!-- box-3 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/payment-buttons-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Payment button</h3>
                <p class="font-mullish text-grayText mt-6">
                    Create copy and collect with payment button. Collect one time or Subscription Payments</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
                    <!-- box-4 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/subscriptions-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Subscriptions</h3>
                <p class="font-mullish text-grayText mt-6">
                    Subscription plans with automatically recurring transactions</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
                   <!-- box-5 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/route-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Route</h3>
                <p class="font-mullish text-grayText mt-6">
                    Split incoming payments automatically to vendors account.</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
                         <!-- box-6 -->
            <div class="w-full min-h-[15rem] relative cursor-pointer">
                <img src="pictures/smart-collect-icon.svg" alt=""
             class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
             transition-all duration-200">
    
             <!-- for logo -->
            <svg
             viewbox="0 0 349.32501220703125 225"
             xmlns="http://www.w3.org/2000/svg"
             preserveAspectRatio="none"
             class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
             duration-200"
             style="stroke-opacity: 0.15">
    
             <path
              d="m 0 6
            a 6 6 0 0 1 6 -6
            h 250.32501220703125
            a 16 16 0 0 1 11 5
            l 77 77 
            a 16 16 0 0 1 5 11
            v 126  
            a 6 6 0 0 1 -6 6
            h -337.32501220703125
            a 6 6 0 0 1 -6 -6
            z"
              fill="#fff"></path>
            </svg>
    
            <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
    
               <div>
                <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                text-[1.375rem]">Smart Collect</h3>
                <p class="font-mullish text-grayText mt-6">
                    Automatically reconcile incoming NEFT,RTGS,IMPS,UPI payments using
                customer identifiers & UPI-Ids</p>
               </div>
                   
               <div class="flex items-center cursor-pointer group">
                <a href="#" class="font-mullish font-bold text-lightBlue500
                group-hover:text-grayBlue transition-all duration-200">
                    Know More ></a>
                
              </div>
    
            </div>
            </div> 
    
           </div>

       </div>

       

    </section>


    <!-- feature section-2 -->
    <section class="bg-[url(pictures/feature-section-2BG.svg)] bg-no-repeat bg-cover
    pb-[300px] mt-14 pt-[10rem]">

       <div class="w-10/12 max-w-[1080px] mx-auto relative pt-4">

           <h2 class="text-white text-center font-mullish font-bold text-[25px] leading-[1.2]">
            Explore Razorpay Banking Buisness</h2>
           <div class="w-6 h-1 bg-greenLight mx-auto mt-4 mb-6"></div>

           <div class="w-full min-h-[480px] flex flex-col relative">

              <img src="pictures/x-flame-1.png" alt="" loading="lazy"
              class="absolute -top-[142px] -left-[140px] w-[200px]">
              <img src="pictures/x-flame-2.png" alt="" loading="lazy"
              class="absolute top-[150px] -right-[180px] w-[270px]">

              <!-- content box -->
              <div class="w-full min-h-[520px]  rounded-md flex relative p-10 py-12 border-slate-700 bg-deepBlue z-20">
                  <!-- left part -->
                  <div class="flex flex-col justify-between w-full">
                    <h3 class="font-mullish text-white font-bold text-[28px] leading-10 max-w-[500px]">
                        Manage your company's finance with
                        <img src="pictures/razorpayX.svg" alt="" loading="lazy"
                        width="168px" height="32px" class="inline">
                        <span class="text-greenLight">Buisness Banking</span>
                    </h3>
                    <ul class="space-y-2 ">
                        <li class="font-mullish flex items-center text-white">
                            <span>> Open a fully digital current account.</span>
                        </li>
                        <li class="font-mullish flex items-center text-white">
                            <span>> Automate payables and compliments payments</span>
                        </li>
                        <li class="font-mullish flex items-center text-white">
                            <span>> Simplify and track spends with corporate cards</span>
                        </li>
                        <li class="font-mullish flex items-center text-white">
                            <span>> View financial insights at a glance</span>
                        </li>
                    </ul>
                    <div class="flex flex-col-reverse md:flex-row items-center space-x-4">
                        <button class="text-white w-full md:w-2/12 bg-lightBlue font-mullish font-bold rounded-md
                        hover:bg-lightBlue500 py-[15px] transition-all duration-200">
                        Sign Up</button>

                        <!-- for link -->
                        <div class="flex items-center cursor-pointer group">
                            <a href="#" class="font-mullish font-bold text-lightBlue500
                            group-hover:text-grayBlue transition-all duration-200">
                                Know more ></a>
                            <i></i>
                        </div>
                    </div>
                  </div>
                 
                    <!-- for right part -->
                    <div>
                        <img src="pictures/buisness-banking.png" alt=""
                        class="absolute max-w-[600px] right-0 bottom-0 hidden md:max-w-[400px] lg:max-w-[600px] md:block lg:block">
                    </div>
                </div>   
                

              <!-- card part -->
               <div class="w-full grid grid-cols-1 lg:grid-cols-3 gap-4 my-14 ">
                <!-- box-1 -->
                <div class="w-full min-h-[15rem] relative cursor-pointer featureCard2 ">
                    <img src="pictures/payment-link-icon.svg" alt=""
                 class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
                 transition-all duration-200">
        
                 <!-- for logo -->
                <svg 
                 viewbox="0 0 349.32501220703125 225"
                 xmlns="http://www.w3.org/2000/svg"
                 preserveAspectRatio="none"
                 class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
                 duration-200 "
                 style="stroke-opacity: 0.15">
        
                 <path
                  d="m 0 6
                a 6 6 0 0 1 6 -6
                h 250.32501220703125
                a 16 16 0 0 1 11 5
                l 77 77 
                a 16 16 0 0 1 5 11
                v 126  
                a 6 6 0 0 1 -6 6
                h -337.32501220703125
                a 6 6 0 0 1 -6 -6
                z"
                  fill="#fff"></path>
                </svg>
        
                <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8 ">
        
                   <div>
                    <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                    text-[1.375rem]">Current Accounts</h3>
                    <p class="font-mullish text-grayText mt-6">
                       Current accounts for fast growing buisness,supported by best technology</p>
                   </div>
                       
                   <div class="flex items-center cursor-pointer group">
                    <a href="#" class="font-mullish font-bold text-lightBlue500
                    group-hover:text-grayBlue transition-all duration-200">
                        Know More ></a>
                    
                  </div>
        
                </div>
                </div>
                 <!-- box-2 -->
                <div class="w-full min-h-[15rem] relative cursor-pointer">
                    <img src="pictures/payment-link-icon.svg" alt=""
                 class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
                 transition-all duration-200">
        
                 <!-- for logo -->
                <svg
                 viewbox="0 0 349.32501220703125 225"
                 xmlns="http://www.w3.org/2000/svg"
                 preserveAspectRatio="none"
                 class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
                 duration-200"
                 style="stroke-opacity: 0.15">
        
                 <path
                  d="m 0 6
                a 6 6 0 0 1 6 -6
                h 250.32501220703125
                a 16 16 0 0 1 11 5
                l 77 77 
                a 16 16 0 0 1 5 11
                v 126  
                a 6 6 0 0 1 -6 6
                h -337.32501220703125
                a 6 6 0 0 1 -6 -6
                z"
                  fill="#fff"></path>
                </svg>
        
                <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
        
                   <div>
                    <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                    text-[1.375rem]">Payouts</h3>
                    <p class="font-mullish text-grayText mt-6">
                       Make simple and reliable payouts to bank accounts</p>
                   </div>
                       
                   <div class="flex items-center cursor-pointer group">
                    <a href="#" class="font-mullish font-bold text-lightBlue500
                    group-hover:text-grayBlue transition-all duration-200">
                        Know More ></a>
                    
                  </div>
        
                </div>
                </div>
                 <!-- box-3 -->
                 <div class="w-full min-h-[15rem] relative cursor-pointer">
                    <img src="pictures/payment-link-icon.svg" alt=""
                 class="bg-lightBlue absolute right-3 top-3 w-12 h-12 rounded-full z-[8]
                 transition-all duration-200">
        
                 <!-- for logo -->
                <svg
                 viewbox="0 0 349.32501220703125 225"
                 xmlns="http://www.w3.org/2000/svg"
                 preserveAspectRatio="none"
                 class="stroke-1 stroke-[#818597] h-full w-full absolute z-[9] transition-all
                 duration-200"
                 style="stroke-opacity: 0.15">
        
                 <path
                  d="m 0 6
                a 6 6 0 0 1 6 -6
                h 250.32501220703125
                a 16 16 0 0 1 11 5
                l 77 77 
                a 16 16 0 0 1 5 11
                v 126  
                a 6 6 0 0 1 -6 6
                h -337.32501220703125
                a 6 6 0 0 1 -6 -6
                z"
                  fill="#fff"></path>
                </svg>
        
                <div class="z-[100] absolute w-full h-full flex flex-col justify-between pl-5 py-6 pr-8">
        
                   <div>
                    <h3 class="font-mullish font-bold text-deepBlueHead leading-[1.2] 
                    text-[1.375rem]">Payroll</h3>
                    <p class="font-mullish text-grayText mt-6">
                       Set your payroll & compliances</p>
                   </div>
                       
                   <div class="flex items-center cursor-pointer group">
                    <a href="#" class="font-mullish font-bold text-lightBlue500
                    group-hover:text-grayBlue transition-all duration-200">
                        Know More ></a>
                    
                  </div>
        
                </div>
                </div>


               </div>
              
              
       </div>
       </div>


    </section>

    <!-- new features -->
    <section class="bg-white relative">

        <div class="relative w-11/12 max-w-[1080px] mx-auto pt-4">

            <img src="pictures/feature-section1-dottedrows.png" alt=""
            class="absolute w-[233px] left-[300px] -top-[6rem] -z-[10]">
            <img src="pictures/feature-section1-dottedrows.png" alt=""
            class="absolute w-[233px] -right-[3.5rem] -top-[6rem] -z-[10]">

            <div class="w-full grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-y-10 gap-x-4 relative z-[10]">
                <!-- item-1 -->
                <div class="relative flex items-center">
                    <h2 class="text-deepBlueHead font-mullish font-extrabold text-4xl leading-[3.375rem]">
                        New in the <span class="text-lightBlue500">Razorpay</span>
                        <br> Product Suite
                    </h2>
                </div>
                <!-- card-1 -->
                <div class="p-10 bg-[url(pictures/instant-settlement-bg.svg)] w-full max-h-[300px] cursor-pointer
                bg-no-repeat hover:scale-105 transition-all duration-200
                hover:bg-[url(pictures/instant-settlement-bghover.svg)] bg-white">
                    <img src="pictures/razorpayXicon.svg" alt="" 
                    class="w-10 h-10">
                    <h3 class="font-mullish font-bold text-lg pt-4">Corporate Cards</h3>
                    <p class="font-mullish py-3 text-grayText leading-normal">
                        Simplify your recurring, international and team expenses with savings on every spend.</p>
                    <div class="flex flex-row items-center cursor-pointer group">
                        <a href=""
                        class="font-mullish font-bold text-lightBlue500
                    group-hover:text-lightBlue transition-all duration-200">Know more ></a>
                    </div>
                </div>
                <!-- card-2 -->
                <div class="p-10 bg-[url(pictures/instant-settlement-bg.svg)] w-full max-h-[300px] cursor-pointer
                bg-no-repeat hover:scale-105 transition-all duration-200
                hover:bg-[url(pictures/instant-settlement-bghover.svg)] bg-white">
                    <img src="pictures/razorpayXicon.svg" alt="" 
                    class="w-10 h-10">
                    <h3 class="font-mullish font-bold text-lg pt-4">UPI-Autopay</h3>
                    <p class="font-mullish py-3 text-grayText leading-normal">
                        Simplify your recurring, international and team expenses with savings on every spend.</p>
                    <div class="flex flex-row items-center cursor-pointer group">
                        <a href=""
                        class="font-mullish font-bold text-lightBlue500
                    group-hover:text-lightBlue transition-all duration-200">Know more ></a>
                    </div>
                </div>
                <!-- card-3 -->
                <div class="p-10 bg-[url(pictures/instant-settlement-bg.svg)] w-full max-h-[300px] cursor-pointer
                bg-no-repeat hover:scale-105 transition-all duration-200
                hover:bg-[url(pictures/instant-settlement-bghover.svg)] bg-white">
                    <img src="pictures/razorpayXicon.svg" alt="" 
                    class="w-10 h-10">
                    <h3 class="font-mullish font-bold text-lg pt-4">Payment Button</h3>
                    <p class="font-mullish py-3 text-grayText leading-normal">
                        Simplify your recurring, international and team expenses with savings on every spend.</p>
                    <div class="flex flex-row items-center cursor-pointer group">
                        <a href=""
                        class="font-mullish font-bold text-lightBlue500
                    group-hover:text-lightBlue transition-all duration-200">Know more ></a>
                    </div>
                </div>
                <!-- card-4 -->
                <div class="p-10 bg-[url(pictures/instant-settlement-bg.svg)] w-full max-h-[300px] cursor-pointer
                bg-no-repeat hover:scale-105 transition-all duration-200
                hover:bg-[url(pictures/instant-settlement-bghover.svg)] bg-white">
                    <img src="pictures/razorpayXicon.svg" alt="" 
                    class="w-10 h-10">
                    <h3 class="font-mullish font-bold text-lg pt-4">QR-Code</h3>
                    <p class="font-mullish py-3 text-grayText leading-normal">
                        Simplify your recurring, international and team expenses with savings on every spend.</p>
                    <div class="flex flex-row items-center cursor-pointer group">
                        <a href=""
                        class="font-mullish font-bold text-lightBlue500
                    group-hover:text-lightBlue transition-all duration-200">Know more ></a>
                    </div>
                </div>
                <!-- card-5 -->
                <div class="p-10 bg-[url(pictures/instant-settlement-bg.svg)] w-full max-h-[300px] cursor-pointer
                bg-no-repeat hover:scale-105 transition-all duration-200
                hover:bg-[url(pictures/instant-settlement-bghover.svg)] bg-white">
                    <img src="pictures/razorpayXicon.svg" alt="" 
                    class="w-10 h-10">
                    <h3 class="font-mullish font-bold text-lg pt-4">Settlements</h3>
                    <p class="font-mullish py-3 text-grayText leading-normal">
                        Simplify your recurring, international and team expenses with savings on every spend.</p>
                    <div class="flex flex-row items-center cursor-pointer group">
                        <a href=""
                        class="font-mullish font-bold text-lightBlue500
                    group-hover:text-lightBlue transition-all duration-200">Know more ></a>
                    </div>
                </div>
            </div>

        </div>

    </section>

    <!-- core features -->
    <section class="w-full bg-[url(pictures/core-features-sectionBg.svg)]
    bg-no-repeat bg-cover bg-center  mt-14 relative pt-[12rem] pb-[12rem]">

      <div class="relative w-11/12 max-w-[1080px] mx-auto pt-4">
        <h2 class="font-mullish font-bold text-2xl text-center text-white">Features</h2>
        <div class="w-6 h-1 bg-greenLight mx-auto mt-4 mb-6"></div>
        <p class="font-mullish text-center text-white mx-auto max-w-[450px]">
            Empower your buisness with all the good tools to accept online payments and instant settlements</p>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-[2rem] mt-8">
            <!-- card-1 -->
           <div>
            <img src="pictures/instant-activation-icon.svg" alt="">
            <h3 class="font-mullish font-bold text-lg my-4 text-white">Instant Activation</h3>
            <p class="font-mullish text-white opacity-80">
                Get activated and transact within 2 minutes.Completely online onboarding with minimum documentation.</p>
           </div>
            <!-- card-2 -->
            <div>
                <img src="pictures/easy-integration.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">Easy Integration</h3>
                <p class="font-mullish text-white opacity-80">
                   With all languages,Integrate and go live with Razorpay in less than an hour.</p>
               </div>
            <!-- card-3 -->
            <div>
                <img src="pictures/api-driven-icon.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">API-Driven</h3>
                <p class="font-mullish text-white opacity-80">
                   Build your buisness with API-Driven automation with zero manual interference.</p>
               </div>
            <!-- card-4 -->
            <div>
                <img src="pictures/simple-pricing.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">100+ payment modes</h3>
                <p class="font-mullish text-white opacity-80">
                    Get activated and transact within 2 minutes.Completely online onboarding with minimum documentation.</p>
               </div>
            <!-- card-5 -->
            <div>
                <img src="pictures/simple-pricing.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">Simple Pricing</h3>
                <p class="font-mullish text-white opacity-80">
                    Our innovative pricing modes with competitive pricing value makes payment easier.</p>
               </div>
            <!-- card-6 -->
            <div>
                <img src="pictures/industry-support-icon.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">Best in Industry Support</h3>
                <p class="font-mullish text-white opacity-80">
                    Always available,e-mail,SMS,Phone,chat based support.</p>
               </div>
            <!-- card-7 -->
            <div>
                <img src="pictures/dashboard-reporting-icon.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">Dashboard Reporting</h3>
                <p class="font-mullish text-white opacity-80">
                    Real time data and insights on your razorpay dashboard.</p>
               </div>
            <!-- card-8 -->
            <div>
                <img src="pictures/secure-icon.svg" alt="">
                <h3 class="font-mullish font-bold text-lg my-4 text-white">Secure</h3>
                <p class="font-mullish text-white opacity-80">
                    Your data is completely secured in Razorpay accounts.</p>
               </div>
        </div>
      </div>

    </section>

    <!-- join razorpay section -->
    <section class="bg-[#f5f8fe] relative pt-40 pb-12 -mt-[200] -z-[100]">

         <div class="w-11/12 max-w-[1080px] mx-auto relative flex flex-col md:flex-row">
             
            <!-- left part -->
            <div class="flex flex-col justify-center w-full md:max-w-[calc(100%-500px)]">
                <h3 class="font-mullish font-bold text-2xl text-deepBlueHead">
                    Join the 50,00,00 buisnesses using Razorpay.</h3>
                <div class="w-6 h-1 bg-greenLight my-4 mb-10"></div>
                <p class="font-mullish opacity-80">
                    We make it easier for you to focus on building great products.
                </p>
                <p class="font-mullish opacity-80 mt-6">
                    Focus on your buisness while we handle the complexities of your payments.
                </p>
            </div>

            <!-- right part -->
            <div class="h-[500px] w-[500px] relative overflow-y-hidden mx-auto">
                <div style="background: linear-gradient(180deg, #f4f8ff, #fff0)"
                class="absolute w-full h-[150px] top-0 z-50"> </div>

                <img src="pictures/comanies.png" alt="" width="500px"
                class="h-auto absolute object-cover companieslist">

                  <div style="background: linear-gradient(0deg, #f4f8ff, #fff0)"                                                                     
                class="absolute w-full h-[150px] bottom-0 z-50">  </div>
            </div>
         </div>

    </section>

    <!-- next feature -->
    <section class="relative">

        <div class="w-11/12 max-w-[1300px] py-20 relative mx-auto">
            <img src="pictures/feature-section1-dottedrows.png" alt=""
            class="absolute w-[200px] top-[8rem] left-[2rem] -z-10">
            <h2 class="font-mullish font-extrabold text-2xl text-deepBlueHead text-center">
                An Experience <br>
                people love to talk about
            </h2>
            <div class="w-6 h-1 bg-greenLight mx-auto my-4"></div>
     

        <!-- left button -->
        <button class="w-[100px] h-[100px] bg-[#f4f8ff] rounded-full absolute left-0 top-1/2 flex justify-center items-center" >
            <div class="font-extrabold text-[40px] text-gray-400 w-[65%] h-[65%] bg-[#f4f8ff] rotate-180
            rounded-full mix-blend-multiply ">
              >
            </div>
        </button>

         <!-- right button -->
         <button class="w-[100px] h-[100px] bg-[#f4f8ff] rounded-full absolute right-0 top-1/2 flex justify-center items-center">
            <div class="font-extrabold text-[40px] text-gray-400 w-[65%] h-[65%] bg-[#f4f8ff]
            rounded-full mix-blend-multiply ">
                >
              </div>
        </button>

        <!-- main body -->
        <div class="flex flex-col md:flex-row max-w-[960px] items-center mx-auto my-20 space-x-[10rem]">

           <!-- left image -->
           <img src="pictures/testimonial.jpg" alt="" height="320px" width="320px"
           class="rounded-xl">

           <!-- right part -->
           <div class="max-w-[400px]">
            <img src="pictures/quotes.svg" alt="" width="35px" height="40px"
            class="-mb-2">
            <p class="font-mullish text-3xl font-extralight">Readymade Closed Wallet Solution For Quick Funds.</p>
            <a href="#" class="text-grayText italic underline">Learn More</a>
            <h3 class="font-mullish font-extrabold text-2xl">David Beddingham</h3>
            <p class="font-mullish font-medium">CEO, XYZ Engineering Company</p>
            <img src="pictures/fake-company-logo.png" alt="" width="80px" height="40px">
           </div>


        </div>

        <!-- dots -->
        <div class="flex flex-row mx-auto justify-center space-x-2">
          
            <!-- dot-1 -->
            <div class="h-[10px] w-[10px] bg-gray-300 rounded-full">

            </div>
             <!-- dot-2 -->
           <div class="h-[10px] w-[10px] bg-blue-600 rounded-full">

           </div>
            <!-- dot-3 -->
            <div class="h-[10px] w-[10px] bg-gray-300 rounded-full">

            </div>
             <!-- dot-4 -->
           <div class="h-[10px] w-[10px] bg-gray-300 rounded-full">

           </div>
            <!-- dot-5 -->
            <div class="h-[10px] w-[10px] bg-gray-300 rounded-full">

            </div>
             <!-- dot-6 -->
           <div class="h-[10px] w-[10px] bg-gray-300 rounded-full">

           </div>
        </div>

    </div>

    </section>

    <!-- testimonial section -->
    <section class="relative bg-[url(pictures/CTABg.svg)] w-full h-full bg-no-repeat bg-cover cta">

       <!-- main content -->
       <div class="w-11/12 relative flex flex-row max-w-[1080px] mx-auto items-center justify-between space-x-20">

         <!-- left part -->
         <div>
            <h2 class="font-mullish font-bold text-2xl text-white">
                Supercharge your buisness with Razorpay
            </h2>
            <div class="w-6 h-1 bg-greenLight"></div>
            <p class="font-mullish text-white">
                Sign up now to experience the future of payments and offers <br>your customer the best checkout experience
            </p>
            <ol type="1" class="flex flex-row gap-8 flex-wrap space-y-2">
                <li class="font-mullish text-white flex flex-row mt-2">
                  <span> > Quick Onboarding</span>
                </li>
                <li  class="font-mullish text-white flex flex-row">
                   <span>> Access to entire product Suite</span>
                </li>
                
                <li  class="font-mullish text-white flex flex-row">
                   > 24X7 Support
                </li>
            </ol>

            <button  class=" text-lightBlue300 py-3 px-4 font-mullish border-lightBlue
            border transition-all duration-200 hover:text-lightBlue500 bg-white rounded-sm text-sm font-extrabold mt-3">
                 Sign up >
            </button>

           
         </div>

         <div>
             <!-- right part -->
             <img src="pictures/ctaImg.svg" alt="" class="hidden lg:block" >
         </div>

       </div>

    </section>

    <!-- footer -->
    <div class="w-full h-[200px] bg-deepBlueHead mt-40 relative flex flex-row justify-between
    ">
    <div>
        <p class="text-white font-bold opacity-40 text-5xl italic absolute left-0 mt-36">Razorpay</p>
    </div>
     <div class="flex gap-4 -mt-16 mr-16">
        <img src="pictures/twitter-icon.svg" alt="" width="30">
     <img src="pictures/linkedin-icon.svg" alt="" width="30">
     <img src="pictures/facebook-icon.svg" alt="" width="30">
     <img src="pictures/github-icon.svg" alt="" width="30">
    </div>
     </div>
   


</body>
</html>
