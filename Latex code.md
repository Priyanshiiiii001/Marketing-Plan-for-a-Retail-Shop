\documentclass[a4paper, table]{article}
\input{General/Preamble} % Loads in the preamble 
\input{General/Settings} % Loads in user defined settings
\begin{document}

% Inserts the front page
\input{Chapters/0. Frontpage}
\newpage

% Generates a ToC without page number
{\hypersetup{linkcolor=black} % Keeps the ToC black even with non-black linkcolor
\tableofcontents\thispagestyle{empty}}
\newpage

% contains inspiration for formatting tables, images, text citations etc.
\input{Chapters/Z. Template} % Feel free to remove / comment out
\newpage

% Generates a list of symbols table
\input{Chapters/0. List of symbols}
\newpage

% Creates the introduction, starting page numbering
\input{Chapters/1. Introduction} \pagenumbering{arabic}
\newpage

% Copy this to add more chapters
\input{Chapters/2. Copy me}
\newpage

\input{Chapters/3. Background}
\newpage

\input{Chapters/4. Related Work}
\newpage

\input{Chapters/5. Approach}
\newpage

\input{Chapters/6. Evaluation}
\newpage

\input{Chapters/7. Discussion}
\newpage

\input{Chapters/8. Conclusions}
\newpage

\end{document}


%%%%%%%%%%% TITLE PAGE

\begin{titlepage}

%%%%%%%%%%% TITLE PAGE

\begin{titlepage}
\setlength{\fboxrule}{2pt} % Border thickness
\setlength{\fboxsep}{3pt} % Space between border and content
\begin{figure}[t]
  \centering
  \begin{adjustbox}{fbox}
    \includegraphics[width=0.5\textwidth]{Figures/0. General/logo.jpeg} 
  \end{adjustbox}
\end{figure}

\begin{tikzpicture}[remember picture,overlay]
  \draw[line width=1pt] ([shift={(0.75cm,-0.75cm)}]current page.north west) rectangle ([shift={(-0.75cm,0.75cm)}]current page.south east);
\end{tikzpicture}

\begin{center}
    \textsc{\LARGE{SCHOOL OF MANAGEMENT\\}}
	\textsc{ \LARGE{Indian Institute of Technology, Mandi\\ }}
	%\textnormal{ \LARGE{Corso di Laurea Triennale/Magistrale in ???\\}}
	\vspace{30mm}
	\fontsize{10mm}{7mm}\selectfont 
    \textup{\uline{Marketing Plan for a Saree Retail Shop}}\\
\end{center}

\vspace{22mm}

\begin{minipage}[t]{0.47\textwidth}
	\textnormal{\large\uline{{\bf Submitted to:\\}}}\break
	{\large Dr. Ashish Bollimbala\\ \\}
 \textnormal{\large\uline{{\bf Submitted by:\\}}}\break
	{\large Group 05}
\end{minipage}\hfill\begin{minipage}[t]{0.47\textwidth}\raggedleft
	\textnormal{\large\uline{{\bf Names:\\}}}
       \begin{itemize}\raggedleft
           \item{Rupjyoti(MB23001)}
           \item {Samarth Sinha(MB23006)}
           \item{Yagyansh(MB23021)}
           \item{Dattatraya Kathare(MB23022)}
           \item{Vishal Kamal(MB23026)}
            \item { Priya Rani(MB23041)
           \item{Bharbee Bora(MB23045)}
           \item{Shivansh Dogra(MB23048)}         
       \end{itemize}
	
\end{minipage}

\vspace{10mm}
\end{titlepage}

\section{EXECUTIVE SUMMARY}
\subsection{Threads of Tradition}

\textbf{\uline{Threads of Tradition}}, a saree retail shop located in Delhi, is poised to redefine the saree shopping experience for women aged 18 to 50 years. With a brand mantra of "Timeless Elegance, Modern Grace," the shop aims to establish itself as a beacon of cultural richness and contemporary fashion. \\
\break
\textbf{Our Vision:} Threads of Tradition is more than a saree retail shop; a cultural hub that curates a collection of sarees embodying the essence of timeless elegance blended seamlessly with modern grace.\\ 
\break
\textbf{Mission Statement:} We commit to provide a diverse range of sarees, accommodating various tastes and preferences. Inclusive styles cater to diverse body types, ensuring every customer finds a saree that complements their unique features. \\
\break
Our comprehensive warranty and guarantee underline our dedication to customer satisfaction, ensuring a seamless and confident shopping experience. With a strategic market segmentation based on demographics, geography, psychographics, and behaviors, Threads of Tradition targets college going girls, office employees, and a diverse consumer base. As the go-to destination for saree enthusiasts, we position ourselves as a distinctive player in the saree retail market, offering an unparalleled shopping experience where every saree tells a story of timeless elegance and modern grace.\\
\break
\begin{figure}[H]
     \centering
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/image a.png}
         \caption{Aesthetics}
         \label{fig:image a}
     \end{subfigure}
     \hfill
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/image b.png }
         \caption{Retail Store}
         \label{fig:image b}
     \end{subfigure}
     \hfill
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/image c.png }
         \caption{Sarees variety}
         \label{fig:image c}
     \end{subfigure}
        \caption{Threads of Tradition}
        \label{fig: Three images}
\end{figure}
\section{CURRENT MARKET SITUATION} \label{section: introduction}

The market size of the sarees market in 2023 is estimated to be around ₹46,400 crore (US\$ 5.9 billion). The market is expected to grow at a CAGR of 6\% over the next three years to reach \₹61,700 crore (US\$ 7.9 billion) by FY25.
The market size of designer sarees in India is estimated to be around ₹10,000 crore (US\$ 1.3 billion) in 2023.\\
\begin{figure}[h]
    \centering
    \includegraphics[width=0.7\textwidth]{Figures/0. General/graph.jpg}
    \caption{Saree Market Growth Projection}
    \label{fig:graph}
\end{figure}


\fontsize{12}{15}\selectfont\textbf{\uline{Market Description and its segment:}}

\begin{enumerate}
    \item \textbf{\uline{Market Distribution:}}
           \begin{figure}[H]
     \centering
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/by age.png}
         \caption{By Age}
         \label{fig: by age}
     \end{subfigure}
     \hfill
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/by demographic.png}
         \caption{By Location}
         \label{fig: By Location}
     \end{subfigure}
     \hfill
     \begin{subfigure}[b]{0.3\textwidth}
         \centering
         \includegraphics[width=\textwidth]{Figures/0. General/by occupation.png}
         \caption{By Occupation}
         \label{fig:By Occupation}
     \end{subfigure}
        \caption{Market Distribution}
        \label{fig: Market Distributio}
\end{figure}
\item \textbf{\uline{Product Portfolio}:}}
\begin{figure}[h]
    \centering
    \includegraphics[width=0.7\textwidth]{Figures/0. General/portfolio.jpg}
    \caption{Types of Sarees with their Market Share}
    \label{fig:Product Portfolio}
\end{figure}
\newpage
Our diverse portfolio to meet every lifestyle ethnic wear requirement includes: - 
\begin{itemize}
    \item Heritage Weaves: Exquisite pure Silk Sarees
    \item Elegant Vibe: Fashionable contemporary Silk sarees
    \item Occasion Aura: Affordable Art Silk occasion wear Sarees
    \item Blend Vogue: Blended Value Silk Sarees
    \item Crafted Elegance: Fine handcrafted Sarees
    \item Party Pulse: Party wear Sarees
    \item Work Ease: Office wear casual Sarees
\end{itemize}

    \item \textbf{\uline{Review of Competition:}}
    With saree becoming a style statement for Indians, the top performing competitors in the designer saree bussiness are:
    \begin{itemize}
        \item \textbf{Sabyasachi:} is one of the most popular and well-respected designer saree brands in India. His sarees are known for their intricate embroidery and rich colors.
        \item \textbf{House of Anita Dongre:} is another popular designer saree brand that is known for its elegant and contemporary designs. Her sarees are often made from lightweight fabrics and are perfect for evening wear.
        \item \textbf{Manish Malhotra:} is a renowned fashion designer who is also known for his beautiful sarees. His sarees are often embellished with sequins, beads, and other embellishments.
        \item \textbf{Label Ritu Kumar:} is a popular designer saree brand that is known for its traditional yet stylish designs. Her sarees are often made from silk or georgette and are perfect for special occasions.
    \end{itemize} 
    In the Normal saree business, the main competitors and their SWOT analysis is given below:
    
\begin{table}[htbp]
    \centering
    \begin{tabular}{|p{3cm}|p{2.5cm}|p{2.5cm}|p{3cm}|p{3cm}|}  
    \hline
 \textbf{Competitor} & \textbf{Strengths}& \textbf{Weaknesses}&\textbf{Opportunities}  &\textbf{Threats} \\
 \hline
 \textbf{Avantra by Trends} & Strong brand name, large retail footprint, ability to leverage economies of scale & Limited saree selection compared to established players, needs to develop a stronger brand identity & Expand saree selection, introduce more affordable options, focus on high-quality sarees and excellent customer service & Changing consumer preferences, increasing competition from online retailers \\
 \hline
 \textbf{Taneira Sarees (Tata's brand)} & Strong brand reputation, wide product range, high-quality fabrics & Limited reach, high prices compared to some competitors & Expand into more cities, introduce more affordable options, enhance online presence & Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion\\
 \hline
 \textbf{Pothy's} & Strong brand presence in South India, extensive experience in the saree market & Limited reach outside of South India, traditional designs & Expand into other parts of India, introduce more contemporary designs, strengthen online presence & Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion.\\
\hline
\end{tabular}\\
\end{table}

\begin{table}[htbp]
    \centering
    \begin{tabular}{|p{3cm}|p{2.5cm}|p{2.5cm}|p{3cm}|p{3cm}|}  
\hline
\textbf{Nallis}	& Strong brand reputation in Chennai, rich heritage	& Limited product range, high prices & Expand product range, introduce more affordable options, enhance online presence & Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion \\
 \hline
 \textbf{Kalyan}	& Large network of stores, wide product range, competitive prices & Average quality fabrics, lack of differentiation & Focus on improving fabric quality, develop a stronger brand identity, enhance online presence &	Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion \\
 \hline
\textbf{ Meena Bazaar} & Affordable prices, large variety of sarees	& Poor quality control, inconsistent customer service	& Improve quality control, enhance customer service, strengthen online presence & Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion\\
 \hline
 \textbf{Fabindia} & Strong focus on sustainability, ethical sourcing, and fair trade	& Limited saree selection, higher prices & Expand saree selection, introduce more affordable options, strengthen online presence &	Changing consumer preferences, increasing competition from online retailers, Reliance Retail's expansion\\
\hline
\end{tabular}\\
\end{table}

\section{OBJECTIVES AND LAYOUT OF SAREE RETAIL SHOP}\label{section: copy me}

\subsection{Sales Measure}
As we are trying to distribute the product in department stores, we are expecting 4,62,00,000 rupees sales of our products after one year after the introduction of our retail store.

\subsection{The Store Design}
\begin{itemize}
    \item {{\textbf{\uline{The Store Atmosphere:}}} Threads of Tradition Store will provide them facilities given below:
    \begin{itemize}
       
    \item Showcasing a variety of sarees in an organized manner, using attractive \textbf{displays} 

    \item Using soothing background \textbf{music} that complements the cultural and elegant feel of saree shopping.

    \item Introducing a subtle, pleasant \textbf{fragrance} to the store to leave a positive and memorable impression on customers.

    \item Training staff to be knowledgeable about different saree types, fabrics, and styles to assist customers effectively and provide a personalized shopping experience.

    \item Ensuring well-equipped and clean \textbf{trial rooms} with ample mirrors, allowing customers to try on sarees comfortably and make informed decisions.

    \item Organizing occasional events, workshops, or demonstrations to engage customers and build a sense of community around the store.

    \item Regularly updating \textbf{window displays} to showcase new arrivals, special collections, or festive themes, attracting potential customers passing by.

    \item \textbf{Digital Integration:} Implementing technology, such as tablets or touchscreens, to provide additional information about the sarees, including their origin, weaving techniques, and care instructions.

    \item \textbf{Offering customization services} or personal shopping assistance to cater to individual preferences and make customers feel valued.
    \end{itemize}  
\end{itemize}

\subsubsection{The Service Blueprint}
The service blueprint here is showing a straightforward customer journey. Upon entering, customers are warmly greeted by salespersons who guide them through the catalog and assist in browsing the saree collection. The selection process involves trying on the chosen saree with the help of the salesperson. \\
The customer's journey concludes as they leave the shop after making the purchase and doing the payment to the cashier. Frontstage actions, visible to the customer, include greetings, catalog presentation, and trying on sarees, while backstage actions, unseen by the customer, involve inventory checks and accounting updates by the salesperson and cashier, respectively.
\begin{itemize}
\item{\textbf{The Line of visibility}} separates frontstage and backstage actions, ensuring customers only witness actions above this line. 
\item{\textbf{The Line of interaction}} delineates customer and employee actions, allowing interactions only at specific touchpoints.
\item{\textbf{The Line of internal interaction }} oversees internal services, managing inventory levels, updating the point-of-sale system, generating sales reports, and facilitating customer satisfaction surveys for internal employees.
\end{itemize}

Click on the given here to open \textbf{The Service Blueprint:} {\url{https://drive.google.com/file/d/1FkKtfg8eJxcrTp-Q51Z9uVTkmN9U3tjV/view?usp=sharing} 
\break

\section{THREATS AND OPPORTUNITIES ANALYSIS} 
For assessing the major threats and opportunities that a saree retail shop might face. Here is the major analysis through SWOT method: \\
\section*{ \uline{SWOT ANALYSIS}  } \label{section: symbols}

\begin{table}[ht]
\rowcolors{2}{gray!10}{white}
\centering

\begin{tabular}[t]
{|m{0.5\textwidth}|m{0.5\textwidth}|}
\toprule
\textbf{STRENGTHS}&\textbf{WEAKNESSES}\\
\bottomrule
\hline
\begin{itemize}
    \item \textbf{Customization Expertise:} Unique point of difference offering customers the ability to tailor sarees to their preferences. 

    \item \textbf{Technological Integration:} Implementation of technology, such as tablets or touchscreens, providing additional information about sarees. Enhances the shopping experience by offering insights into the origin, weaving techniques, and care instructions.

    \item \textbf{Inclusive Styles:} Acknowledgment and catering to diverse body types and style preferences.
    Strengthens inclusivity, ensuring a broad customer base.

\end{itemize}&
\begin{itemize}
    \item \textbf{Limited Online Presence:} If Threads of Tradition is not adequately leveraging e-commerce and digital platforms, it may miss out on a significant market share, especially among tech-savvy customers.

    \item \textbf{Limited Geographical Presence:} Currently situated in Delhi, expansion to other regions may be needed for broader market reach.

    \item \textbf{Age Demographic Focus:} Primarily targets women aged 18 to 50; diversifying the target demographic might be beneficial.

\end{itemize}\\
\toprule
\textbf{THREATS}&\textbf{OPPORTUNITIES}\\
\bottomrule

\begin{itemize}
    \item \textbf{Supply Chain Challenges:} Sourcing quality materials and ensuring a reliable supply chain are crucial. Any disruptions could affect the ability to meet customer demand

    \item \textbf{Economic Downturn:} Economic uncertainties affecting consumer spending.
Strategies needed to adapt to changing economic conditions.


    \item \textbf{Changing Fashion Trends:} Rapid changes in fashion trends impacting consumer preferences.
Agility required to adapt to evolving fashion demands.

\end{itemize}&\begin{itemize}
    \item \textbf{Growing E-commerce Market:} Leverage the increasing trend of online saree shopping through an enhanced online platform. Reach a broader audience beyond the local market.

    \item \textbf{Collaboration with more Famous Fashion Influencers:} Partnering with fashion influencers to promote unique saree collections. Capitalize on influencer marketing to increase brand visibility.


    \item \textbf{Product Variety:} We can launch more new regional types of sarees to attract diverse population.


\end{itemize}\\

\bottomrule

\end{tabular}
\end{table}

\section{MARKETING STRATEGY}\label{section: MARKETING STRATEGY}
\subsection{Value Proposition}
\begin{enumerate}
   
    \item \textbf{\uline{In-Store Experience:}} The ambiance and layout of Threads of Tradition are meticulously designed to create a welcoming and visually appealing environment.

    \item \textbf{\uline{Customer Engagement:}} Loyalty programs, promotions, and events serve as the pillars of customer engagement for Threads of Tradition.

    \item \textbf{\uline{Brand Communication:}} Consistency in communication is paramount for Threads of Tradition. Through various channels, the brand consistently communicates its values and offerings, ensuring alignment with the cultural and fashion preferences of the target audience.
\end{enumerate}
\subsubsection{Segmentation and Targeting}
\textbf{\uline{Target Market:}} 
\begin{itemize}
    \item \textbf{Based On Income:}
        \begin{itemize}
            \item High-Income Segment: We will introduce High end Luxury Sarees which will be exclusive with intricate designs and premium materials for affluent customers. Also, Our Bridal Saree Collection will focus on luxurious bridal sarees with intricate embellishments.
            \item Middle-Income Segment: This segment will focus on Occasional Wear Sarees and in this we will provide a variety of sarees suitable for weddings, festivals, and special occasions at moderate price points.
        \end{itemize}
    \item\textbf{Based on Age:}
        We will be targeting women in the age group of 18-50 years which will include household, Working class and Fashion Enthusiasts.
    \item\textbf{Based On Psychology:}
        \begin{itemize}
            \item Lifestyle: This segment includes Traditionalists and Modern-Trendy women who may classic and timeless saree designs.
            \item Occasion: This segment include Wedding Shoppers and Casual Wear Seekers 
            \item Urban Vs. Rural Preferences: Here we are focusing more on Urban customers.
        \end{itemize}   
\end{itemize}

\subsection{Branding Process:}
The branding process involved creating a unique identity that resonates with the diverse age groups of women across India, ensuring the saree shopping experience is not only memorable but also reflects the cultural significance and modern aesthetic preferences.

\subsection{Brand Mantra:}
Our Brand Mantra is \textbf{\uline{"Timeless Elegance, Modern Grace"}}. It signifies to succinctly capture the heart and soul of Threads of Tradition, emphasizing the brand's commitment to preserving tradition while embracing contemporary elegance.

\subsection{Brand Logo:}
\begin{figure}[h]
    \centering
    \includegraphics[width=0.2\textwidth]{Figures/0. General/LOGO.png}
    \label{fig:LOGO}
\end{figure}

\subsection{Frame of Reference:}
\subsubsection{\uline{Points of Parity:}}
\begin{itemize}
   \item Threads of Tradition recognizes the necessity of providing a wide variety of sarees, meeting the basic expectations of customers looking for diverse choices.
    \item The positive association of Threads of Tradition with high-quality fabrics and craftsmanship is a correlational point of parity, as it is linked to positive brand perceptions.
    \item By offering unique saree collections and customization, Threads of Tradition aims to turn competitors' strengths into its own point of parity, emphasizing its distinctiveness in the market.
\end{itemize}
\subsubsection{\uline{Points of Difference:}}
\begin{itemize}
    \item Customers can tailor their sarees to suit personal preferences, ensuring a unique and personalized fashion statement.The expertise in customization is a deliverable that sets Threads of Tradition apart, showcasing the brand's commitment to fulfilling individual customer needs.
    \item Threads of Tradition implements technology, such as tablets or touchscreens, to provide additional information about the sarees, including their origin, weaving techniques, and care instructions.
    \item Threads of Tradition takes pride in creating a personalized and memorable saree shopping experience, where customer feedback is not just valued but actively sought, ensuring continuous improvement and a commitment to exceeding expectations.
\end{itemize}

\subsection{Brands’ Role for Consumers:}
\begin{enumerate}
    \item Set and Fulfill Expectations
    \item Transparent information about materials, craftsmanship, and fair pricing.
   \item The shop layout and customer service designed to simplify the decision-making process for customers.
    \item  The brand seeks to embed itself into the lifestyle and self-expression of its customers.
\end{enumerate}

\subsection{Brands’ Role for the Saree Retail Shop:}
\begin{itemize}
    
    \item \textbf{\uline{Create Brand Loyalty:}} Our Loyalty programs and personalized shopping experiences are integral components of our strategy to encourage repeat business and foster a lasting connection with our customers.\\
    \textbf{\uline{Trends of Tradition Loyalty Program (Elegance Rewards) are:}}
    \begin{itemize}
    \item \textbf {Silver Elegance:}
        \begin{itemize}
            \item Customers achieve Silver Elegance status with an annual purchase of Rs. 5,000 - 20,000. 
            \item Customers can earn 1\% in Silk Rewards for every purchase, redeemable towards silk sarees.
            \item Highlight of Threads of Tradition is exclusive access to special promotions and events e.g. Birthday Bonanza: Enjoy an extra 5\% special discount on your birthday.
        \end{itemize}
    \item \textbf {Gold Elegance::}
        \begin{itemize}
            \item  Customers can achieve Gold Elegance status with an annual purchase of Rs. 20,000 - 50,000. 
            \item Our customers can enjoy 2\% in Silk Rewards for every purchase, redeemable towards silk sarees
            \item Early access to new collections and private sales is provided.
        \end{itemize}
    \item \textbf {Platinum Elegance::}
        \begin{itemize}
            \item Customers can achieve Platinum Elegance status with an annual purchase exceeding Rs. 50,000.
            \item Complimentary personalized shopping consultations are provided.
            \item Our customers can enjoy 4\% in Silk Rewards for every purchase, redeemable towards silk sarees
            \item  Exclusive access to sneak peeks, previews, and limited-edition collectionsis provided.
            \item Referral Rewards: Bonus points for referrals (100 silk reward) and the referee on their first purchase(min purchase of Rs.5000)
        \end{itemize} 
    \end{itemize}

    \item \textbf{\uline{Securing Competitive Advantage:}} Unique offerings, personalized services, and a distinctive overall brand experience set the retail shop apart from competitors, ensuring a unique value proposition in the market.

    \item \textbf{\uline{Organize Inventory and Accounting:}}The brand operates with efficient systems in place for inventory tracking and accounting. These systems are seamlessly integrated with the brand's clear identity, supporting the operational backbone of the retail shop.  

    \item \textbf{\uline{Simplify Product Handling:}} Efficiency is key in the operational aspects of Threads of Tradition. Streamlined inventory management ensures easy handling and accessibility of sarees, contributing to a seamless and organized shopping experience.

\end{itemize}

\subsection{Market Mix }
\subsubsection{Product}
Threads of Tradition is a saree retail store that offers different types of varieties that are: Kanjeevaram, Banarasi , Patola , Chanderi, Cotton, Chiffon, Georgette and Bandhani Saree. Our diverse portfolio to meet every lifestyle ethnic wear requirement includes Heritage Weaves, Elegant Vibe, Occasion Aura, Blend Vogue, Crafted Elegance, Party Pulse and Office wear casual Sarees.\\
These sarees are made from high-quality fabrics and have unique designs and patterns that reflect the rich cultural heritage of India. Threads of Tradition also provides customization options for its customers, such as choosing the thread options like gold and silver zari, style of the saree, as well as adding embellishments, embroidery, or prints.
\subsubsection{Pricing}
 The expected different range for our saree products targeting every day lifestyle and ethnic wear are: 
     \begin{table}[h] 
    \centering
    \begin{tabular}{ |p{4cm}|p{4cm}|p{4cm}| }
        \hline
        \textbf{Types} & \textbf{Price Range(in Rupees}   \\
        \hline
        Heritage Weaves  & 15000-100000+\\
         \hline
         Elegant Vibe & 5000-20000 \\
        \hline
        Occasion Aura & 2000-5000 \\
         \hline
        Blend Vogue & 1500-2500 \\
        \hline
       Crafted Elegance & 2500-10000\\
        \hline
        Party Pulse& 6000-18000 \\
        \hline
       Work Ease& 1000-2500 \\
        \hline
         \end{tabular}
         \end{table}\\
\subsubsection{Place}
\textbf{"Threads of Tradition"}, our saree retail shop, is all set to make its mark in the vibrant market of Lajpat Nagar, New Delhi. Positioned strategically, it caters to saree enthusiasts seeking a haven for their traditional wear needs. With a spacious layout spanning 2000 sq. ft., our store is designed to provide a rich and immersive shopping experience. The strategic location takes advantage of the bustling market's daily footfall of 1-1.25 lakh shopping enthusiasts, particularly drawn to traditional wear and personalized offerings.
\subsubsection{Promotion}
\begin{itemize}
\item\textbf{\uline{Through Brand Mantra:}} For our retail store, we are trying to enter our customer’s mind through our brand mantra “Timeless Elegance, Modern Grace” 
\item\textbf{\uline{Digital Promotion:}} Our other promotional activities include advertising; most focus is on social media promotion we will have our own social media handle in Instagram/Facebook. We could use the Google AdSense, Facebook AdSense and Influencers on Instagram/Facebook to connect with the customers. 
\item\textbf{\uline{Direct promotion:}} For reaching out to customers in the real world we are planning to market mostly in events such as trade fares.
 Apart from that, we are also planning to market in local newspaper, pamphlets distribution and banner hoardings.
 
\end{itemize}

\section{BUDGET} \label{section: copy me}

The Expense and Income Summary of The Threads of Tradition Shop is given below:\\

\textbf{Click here} on this link: \\{\url{https://docs.google.com/spreadsheets/d/1ZWnfm1Kdv6fzgRAGjT8RHyleaPcvRYIa/edit?usp=drive_link&ouid=110312209839552344299&rtpof=true&sd=true } \\
to open The Expense and The Income Statement of Threads of Tradition.

The Final Summary of Budget from the above Excel file is:\\
\begin{tabular}{ |p{7cm}|p{7cm}| } 
\hline
\multicolumn{2}{|c|}{\textbf{Expense Statement}} \\
\hline
\textbf{Type of Expense} & \textbf{Amount(in rupees)} \\
\hline
Operating & 5620000 \\
\hline
Non Operating & 2200124 \\
\hline
Setup cost & 2910000 \\
\hline
Inventory & 29700000 \\
\hline
\textbf{Total} & 40430124 \\
\hline
\end{tabular}\\
\break
\begin{tabular}{ |p{7cm}|p{7cm}| } 
\hline
\multicolumn{2}{|c|}{\textbf{Income Statement}} \\
\hline
\textbf{Type of Expense} & \textbf{Amount(in rupees)} \\
\hline
Marketing & 40500000 \\
\hline
Organic footfall & 5625000 \\
\hline
\textbf{Total} & 46125000 \\
\hline
\end{tabular}\\
\break
\begin{tabular}{ |p{7cm}|p{7cm}| } 
\hline
\multicolumn{2}{|c|}{\textbf{Profit-Loss Statement}} \\
\hline
\textbf{Type of Expense} & \textbf{Amount(in rupees)} \\
\hline
EBIT & 5694876 \\
\hline
Tax slab(<400cr)@25\% & 1423719  \\
\hline
PAT(Net Profit) & 4271157  \\
\hline
\end{tabular}\\

\section{CONTROL} \label{section: copy me}

\textbf{\uline{Key Performance Indicators (KPIs):}} are crucial for evaluating progress and pinpointing areas for enhancement in our retail saree store. Pertinent KPIs include:
\begin{itemize}
    \item \textbf{Sales Metrics:} Keep tabs on total sales and sales categorized by saree type to understand saree popularity and customer preferences.
    \item\textbf{Social Media Engagement:} Monitor growth in followers, likes, shares, and comments on social media posts to assess our online presence and customer engagement.
    \item\textbf{Customer Acquisition Cost (CAC):} Calculate the cost of acquiring new customers using the formula:\\
\end{itemize}

\textbf{\uline{For Effective Management:}} 

\begin{itemize}
    \item\textbf{Sales Tracking System:} Implement a sales tracking system to analyze sales by types of saree and customers, and recognizing customer trends.
    \item\textbf{Inventory Management System:} like Just-in-Time (JIT) and Days Sales of Inventory (DSI) to track stock levels, reorder points, and product turnover, preventing overstocking or understocking as well as ensuring that customer demand is met.
    \item\textbf{Customer Relationship Management (CRM):} help monitoring customer interactions, purchase history, after-sale services, and preferences. 
    \item\textbf{Customer lifetime value (CLV):} Estimating the potential monetary value customers may generate over their tenure, the store can tailor marketing strategies, enhance customer experiences, and allocate resources effectively to foster long-term loyalty and sustainable growth.
    \item\textbf{Marketing Campaign Tracking Surveys:} Employ surveys to track the performance of marketing campaigns, enabling us to fine-tune strategies based on campaign effectiveness.   
\end{itemize}
Now, a sample survey questionnaire followed by our saree shop to get better customer satisfaction insights is:\\

\textbf{Click here} on this link: \\{\url{https://drive.google.com/file/d/1o8Pnr0xBIgu0pl1N4EXpKEtLnKLluuNW/view?usp=drive_link } to open the Survey.

\section{REFERENCES} \label{section: copy me}
1. \url{https://www.livafluidfashion.com/pdf/India_Saree_Trends.pdf}

2. \url{https://delhiplanning.delhi.gov.in/sites/default/files/Planning/ch._19_demographic_profile.pdf}

3. \url{https://indiatradefair.com/uploads/editor_images/space_booking.PDF}

4. \url{https://www.modash.io/find-influencers/india/delhi/fashion}

5. \url{https://www.statista.com/statistics/1328748/india-saree-market-size/}

6. \url{https://www.esilk.net/EnWeb/TempleteList.aspx?id=139}

\subsection{\textbf{Threads of Tradition Online Catalogue:}}
\begin{figure}[h]
    \centering
    \includegraphics[width=0.3\textwidth]{Figures/0. General/qrcode.jpg}
    \label{fig:qrcode}
\end{figure}
