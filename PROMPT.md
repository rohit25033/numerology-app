Build a complete numerology web app with the following specifications:

## Tech Stack
- Backend: Python Flask (app.py)
- Frontend: templates/index.html (single page, vanilla HTML/CSS/JS)
- PDF: reportlab library
- Include requirements.txt

## Chaldean Letter Values
1: A, I, J, Q, Y
2: B, K, R
3: C, G, L, S
4: D, M, T
5: E, H, N, X
6: U, V, W
7: O, Z
8: F, P
(No letter = 9 in Chaldean. 9 is sacred.)
Vowels: A, E, I, O, U

## Number Reduction Rule
Sum all digits repeatedly until single digit. EXCEPT keep 11, 22, 33 as master numbers.

## Calculations
1. Mulank (Psychic Number): birth day reduced (e.g. 28 = 2+8 = 10 = 1)
2. Bhagyank (Destiny Number): DD+MM+YYYY all digits summed and reduced
3. Connection Number: Mulank + Bhagyank reduced
4. Personality Number: Chaldean values of CONSONANTS in full name, summed, reduced
5. Soul Urge Number: Chaldean values of VOWELS in full name, summed, reduced
6. Success Number: Personality + Soul Urge reduced
7. Maturity Number: Mulank + Bhagyank reduced
8. Personal Year: birth DD + birth MM + current year, all digits summed, reduced
9. Lo Shu Grid: 3x3 grid (4,9,2 / 3,5,7 / 8,1,6), check which digits appear in DOB (DDMMYYYY)

## Report Sections (in this exact order)
1. Mulank - characteristics, favourable/unfavourable periods, lucky colours
2. Bhagyank - personality traits
3. Love & Sex Style
4. Connection Number
5. Personality Number
6. Soul Urge Number
7. First Letter of Name (A-Z)
8. Success Number - qualities + challenges
9. Maturity Number
10. Personal Year - positive results, negative results, luck %
11. Career Numerology - traits, fields, strengths, challenges
12. Lo Shu Grid - visual 3x3 table + interpretations for present numbers
13. Missing Numbers - impact + full remedy for each

## Content Database (hardcode all numbers 1-9 for every section)

### MULANK
1 (Sun): Born leader, radiates confidence, ambitious, bold, straightforward. Centre of attraction. Freedom lover. Avoid ego and overconfidence. Favourable: Mar 21-Aug 20. Unfavourable: Oct 15-Dec 25. Lucky color: Red.
2 (Moon): Sensitive, intuitive, emotional, diplomatic. Natural peacemaker. Highly imaginative. Can be indecisive and overly sensitive. Favourable: Jul 20-Aug 20. Unfavourable: Oct 15-Nov 14. Lucky color: White, Silver, Cream.
3 (Jupiter): Extremely ambitious, self-motivated, social, cheerful, religious. Great communicator and multitasker. Can be bossy. Favourable: Mid Feb-Mid Mar and Nov 25-Dec 25. Unfavourable: Oct-Nov. Lucky color: Yellow, Golden.
4 (Rahu): Practical, hardworking, disciplined, unconventional thinker. Challenges existing norms. Can be stubborn and rigid. Favourable: Jun 21-Aug 20. Unfavourable: Jan 14-Feb 14. Lucky color: Electric blue, Grey.
5 (Mercury): Versatile, quick-witted, adaptable, loves freedom and travel. Excellent communicator. Can be restless and inconsistent. Favourable: Jun 21-Aug 20, Sep 21-Oct 20. Unfavourable: Dec 25-Jan 14. Lucky color: Green, Light grey.
6 (Venus): Loving, caring, family-oriented, artistic, harmonious. Natural nurturer. Can be possessive and self-sacrificing. Favourable: Apr 20-May 20. Unfavourable: Oct 15-Nov 14. Lucky color: Pink, Light blue, White.
7 (Ketu): Spiritual, introspective, analytical, mysterious. Seeker of truth. Can be isolated and melancholic. Favourable: Jul 20-Sep 20. Unfavourable: Dec 25-Jan 14. Lucky color: Lavender, Violet.
8 (Saturn): Ambitious, disciplined, powerful, material-minded. Born for power and authority. Can be workaholic and ruthless. Favourable: Dec 25-Jan 14. Unfavourable: Mar 21-Apr 20. Lucky color: Dark blue, Black, Brown.
9 (Mars): Courageous, energetic, passionate, humanitarian. Natural warrior. Can be aggressive and impulsive. Favourable: Mar 21-Apr 20. Unfavourable: Oct 15-Nov 14. Lucky color: Red, Crimson.

### BHAGYANK
1 (Sun): Destiny of leadership and individuality. Blessed with originality and pioneering spirit. Must develop independence and avoid dependence on others. Success through self-effort.
2 (Moon): Destiny of harmony and cooperation. Natural diplomat and mediator. Success through partnerships and teamwork. Must avoid over-sensitivity and indecision.
3 (Jupiter): Destiny of creativity and self-expression. Blessed with communication skills and optimism. Success through creative pursuits and social connections. Avoid scattering energy.
4 (Rahu): Mental power, practicality, reads between the lines. Plans often get disrupted. Fickle focus due to Rahu influence. Unconventional ideas that take time to be accepted. Rely on brain over brawn. Maintain focus for miracles.
5 (Mercury): Destiny of freedom and change. Highly adaptable, loves travel and variety. Success through versatility and communication. Must develop discipline and consistency.
6 (Venus): Destiny of love and responsibility. Natural caretaker and harmonizer. Success through service to family and community. Must avoid martyrdom and possessiveness.
7 (Ketu): Spirituality and intuition. Becomes everyone's favourite naturally. Healer by nature - talking to them comforts others. Wisdom and deep knowledge. Foreign recognition likely. If married before 28, marital issues possible. Drawn to occult sciences later in life.
8 (Saturn): Destiny of power and material achievement. Must overcome obstacles to reach success. Karmic lessons around money and authority. Great potential for business and leadership.
9 (Mars): Destiny of humanitarian service. Strong idealism and compassion. Success through helping others and fighting for causes. Must channel aggression productively.

### LOVE & SEX STYLE (by Bhagyank)
1: Passionate and dominant lover. Strong physical attraction. Independent in relationships - needs space. Can be self-centered. Best with partners who admire their strength.
2: Romantic, tender, and deeply emotional. Craves intimacy and closeness. Highly sensitive to partner's needs. Can become too dependent. Needs reassurance.
3: Playful, flirtatious, and creative in love. Needs mental stimulation and fun. Can be inconsistent in emotions. Keeps relationships lively with humor and spontaneity.
4: Deliberate, slow and steady buildup of intensity. Loyalty is unwavering. Overthinking can make lovemaking feel like a duty. Balance intellectual approach with willingness to explore. Practical yet deeply committed.
5: Adventurous and experimental lover. Needs variety and excitement. Can be commitment-phobic. Charming and irresistible. Best with open-minded partners.
6: Deeply romantic, sensual, and devoted. Creates beautiful experiences for partner. Gives everything in love. Can be overly possessive. Needs to feel cherished and valued.
7: Dreamy and romantic, harbors secret desire for spiritual connection. Intellect holds great importance. Trust is essential. Avoid overanalyzing or you miss profound connections. Mystery and deep thinking characterize your style.
8: Intense and powerful lover. Views relationships as partnerships of equals. Can be controlling. Needs loyalty and respect. Deeply passionate beneath the serious exterior.
9: Passionate, generous, and idealistic in love. Can fall hard and fast. Prone to putting partners on pedestals. Needs to avoid being too self-sacrificing. Deeply loyal once committed.

### CONNECTION NUMBER (1-9)
1: Step into your leadership role with confidence. Trust your instincts and pioneering ideas. Develop your independence and unique identity. Avoid imitating others - your originality is your greatest strength.
2: Nurture your relationships with care and sensitivity. Develop your intuition and trust your inner voice. Practice diplomacy in all interactions. Your gift for harmony can create beautiful partnerships.
3: Cultivate creativity through dancing, acting, poetry, or writing. Nurture self-confidence and embrace a more relaxed attitude. Draw inspiration from successful creative people around you.
4: Enhance your reliability and punctuality by incorporating practical, organised, systematic approaches. Prioritise attention to details. Engage in outdoor and physical activities for self-discovery. Steer clear of procrastination.
5: Embrace change and seek new experiences. Develop your communication skills and versatility. Travel, learn new skills, and stay curious. Your adaptability is your superpower.
6: Focus on creating harmony in your home and relationships. Nurture your artistic side and beautify your environment. Practice unconditional love and service. Family bonds are your foundation.
7: Deepen your spiritual practice and inner life. Spend time in solitude for reflection and study. Trust your powerful intuition. Explore metaphysical subjects and seek deeper meanings in life.
8: Channel your ambition into structured, long-term goals. Develop financial intelligence and business acumen. Balance material pursuits with personal relationships. Your persistence will bring great rewards.
9: Embrace your humanitarian impulses and serve a greater cause. Release what no longer serves you and make room for new experiences. Your compassion and wisdom inspire those around you.

### PERSONALITY NUMBER (1-9)
1: You project an image of confidence, authority and independence. People see you as a natural leader with a strong presence. Your pioneering spirit and bold approach to life make you stand out in any crowd.
2: You project an image of gentleness, diplomacy and cooperation. People see you as a peacemaker and a good listener. Your warm, caring nature makes others feel comfortable and understood in your presence.
3: Your energy radiates vitality and vibrancy. You possess a captivating and inspiring aura that uplifts those around you. Your charming nature and infectious personality make you a delight to be with. Your wit makes you the centre of attention.
4: You project an image of reliability, stability and practicality. People see you as dependable and hardworking. Your methodical and organised approach to life gives others confidence that things will be done right.
5: You possess a remarkable ability to stimulate and energize those around you. Social gatherings come alive in your presence as you infuse them with fresh and original ideas. Your conversations are characterized by a delightful blend of novelty, wit and charismatic charm.
6: You project an image of warmth, nurturing and responsibility. People see you as caring, supportive and trustworthy. Your natural ability to create harmony and beauty makes you a beloved presence in any setting.
7: You project an image of mystery, depth and intelligence. People are drawn to your quiet wisdom and introspective nature. Your analytical mind and spiritual depth give you an aura of profound understanding.
8: You project an image of power, authority and success. People see you as ambitious, capable and in control. Your executive presence and business-like manner command respect and inspire confidence.
9: You project an image of wisdom, compassion and universal love. People see you as inspiring, idealistic and deeply human. Your broad perspective and genuine concern for others makes you a natural humanitarian.

### SOUL URGE NUMBER (1-9)
1: Deep desire to be independent and lead. Want to be first, original and self-sufficient. Crave recognition for unique accomplishments. Inner drive to stand on own two feet.
2: Deep desire for love, harmony and connection. Want peace in all relationships. Crave partnership and belonging. Inner need to feel needed and appreciated.
3: Deep desire to express yourself creatively. Want to entertain, inspire and uplift others. Crave social connection and joyful experiences. Inner need for appreciation of creative gifts.
4: Want to be realistic, practical and intelligent. Want to create fixed assets and securities at earliest in life. Always want to remain organised. Want to be respected everywhere. Inner desire to serve others systematically.
5: Deep desire for freedom and adventure. Want to experience everything life has to offer. Crave variety, travel and new experiences. Inner need to feel unrestricted and alive.
6: Every penny is for family. Wants beautiful things in life. Wants to be cherished by family and close group of friends. Offers genuine help to others. Life sums up to Love, Friendship and Family.
7: Deep desire for knowledge and spiritual truth. Want to understand the mysteries of life. Crave solitude and deep thinking. Inner need to find meaning beyond the material world.
8: Deep desire for power, wealth and achievement. Want to build something lasting and significant. Crave recognition for accomplishments. Inner drive to succeed in material world.
9: Deep desire to make the world a better place. Want to give freely and serve humanity. Crave universal love and acceptance. Inner need to live a life of meaning and purpose.

### FIRST LETTER (A-Z)
A: Natural leader with strong willpower. Independent, determined and ambitious. Highly creative with original ideas. Can be stubborn and self-centered at times. Strong drive to succeed on own terms.
B: Sensitive, cooperative and emotionally intuitive. Natural mediator with strong people skills. Deeply caring and devoted in relationships. Can be overly sensitive and indecisive.
C: Creative, expressive and optimistic. Wonderful communicator with a great sense of humor. Naturally social and uplifting to others. Can scatter energy and avoid difficult tasks.
D: Practical, disciplined and hardworking. Dependable and thorough in all endeavors. Strong builder with great organizational skills. Can be stubborn and resistant to change.
E: Versatile, freedom-loving and quick-minded. Excellent communicator and natural adventurer. Highly adaptable to new situations. Can be restless and inconsistent.
F: Responsible, caring and family-oriented. Natural nurturer with a strong sense of duty. Artistic and appreciates beauty. Can be self-sacrificing and worrisome.
G: Analytical, introspective and spiritually inclined. Deep thinker with strong intuition. Seeks perfection and truth. Can be secretive and overly critical.
H: Sociable, enjoyable to be around, and possessing notable intelligence. Highly prioritises freedom and independence. Remarkable sense of humour adds to their charm. Nurturing and empathetic towards others. Strong affinity for good music, food, drinks and art. Can become overly ambitious and selfish. Tires easily in physical activities.
I: Compassionate, artistic and highly sensitive. Deep humanitarian instincts. Strongly intuitive and emotionally aware. Can be moody and self-pitying.
J: Initiator with strong leadership qualities. Independent, determined and resourceful. Excellent at starting new projects. Can be impatient and domineering.
K: Highly cooperative with a charismatic personality. In touch with emotions and relies on intuition. Excels at entertaining others. Deep love for nurturing people and emotions. Ability to motivate and inspire. May encounter sudden events or losses. Fortunate financially with potential to become wealthy.
L: Analytical, detail-oriented and highly intelligent. Strong sense of justice and fairness. Excellent problem-solver. Can be overly critical and indecisive.
M: Hardworking, practical and deeply responsible. Strong maternal/paternal instincts. Highly reliable and dependable. Can be rigid and overly cautious.
N: Creative, intuitive and imaginative. Strong mental energy and quick thinking. Passionate and intense in pursuits. Can be nervous and unpredictable.
O: Responsible, compassionate and deeply committed. Strong sense of justice and fairness. Natural counselor and advisor. Can be self-righteous and overly cautious.
P: Intellectual, philosophical and spiritually aware. Seeks knowledge and deeper understanding. Strong powers of concentration. Can be secretive and isolated.
Q: Powerful, mysterious and highly intuitive. Strong leadership with unique perspectives. Excellent at reading situations. Can be suspicious and demanding.
R: Compassionate, humanitarian and deeply responsible. Strong work ethic and practical skills. Inspires others through example. Can be scattered and overly emotional.
S: Intense, emotional and highly magnetic. Natural initiator with strong willpower. Excellent at transformation and renewal. Can be secretive and obsessive.
T: Sensitive, intuitive and spiritually inclined. Natural healer and peacemaker. Strong sense of rhythm and creativity. Can be self-doubting and overly emotional.
U: Highly intuitive, humanitarian and universally minded. Strong spiritual awareness. Generous and compassionate. Can be impractical and escapist.
V: Practical, hardworking and highly capable. Excellent builder and organizer. Strong business instincts. Can be rigid and workaholic.
W: Versatile, communicative and highly social. Natural entertainer and storyteller. Quick-witted and adaptable. Can be scattered and superficial.
X: Intense, passionate and highly perceptive. Strong regenerative abilities. Excellent at research and investigation. Can be obsessive and secretive.
Y: Independent, spiritual and highly intuitive. Strong desire for freedom and truth-seeking. Natural philosopher. Can be indecisive and isolated.
Z: Optimistic, energetic and highly determined. Natural leader with infectious enthusiasm. Excellent at completing what others start. Can be impatient and domineering.

### SUCCESS NUMBER (1-9)
1: Qualities - Leadership, originality and pioneering spirit define your success path. You have the drive to be first and blaze new trails. Your confidence and determination inspire others. Challenges - Avoid arrogance and learn to collaborate. Success grows when you empower others rather than dominating them.
2: Qualities - Diplomacy, cooperation and sensitivity are your keys to success. You excel in partnerships and create harmony wherever you go. Your intuition is a powerful guide. Challenges - Overcome indecisiveness and lack of confidence. Learn to stand firm in your own worth and value.
3: Qualities - Dynamic, creative and social. You convey the image of the joker, the entertainer and the mastermind of creativity. Your personality is characterised by humour, wit, intelligence and sociability. Inherently joyful, you spread happiness to those around you. Challenges - Fear of criticism or emotional baggage may suppress your dreams. The strong desire for social acceptance can lead you to compromise your remarkable creative abilities.
4: Qualities - Discipline, organization and practicality define your success. You build lasting foundations and see projects through to completion. Your reliability makes you invaluable. Challenges - Avoid rigidity and learn to adapt. Balance hard work with rest and relationships.
5: Qualities - Versatility, freedom and communication are your strengths. You adapt quickly and excel in dynamic environments. Your ability to connect with diverse people opens many doors. Challenges - Develop consistency and follow-through. Scattered energy and restlessness can undermine your many talents.
6: Qualities - Responsibility, nurturing and harmony define your success. You excel at creating beautiful, functional environments and caring for others. Your artistic sensibility and warm heart draw people to you. Challenges - Avoid martyrdom and learn healthy boundaries. Your tendency to sacrifice yourself for others can lead to resentment.
7: Qualities - Wisdom, analysis and spiritual insight are your success keys. You excel at research, investigation and finding hidden truths. Your depth of understanding gives you unique perspectives. Challenges - Avoid isolation and over-analysis. Share your insights with the world rather than keeping them to yourself.
8: Qualities - Ambition, authority and material mastery define your success. You excel at business, leadership and building financial security. Your executive abilities and determination create lasting achievements. Challenges - Avoid workaholism and ruthlessness. True success includes fulfilling personal relationships and good health.
9: Qualities - Compassion, wisdom and universal understanding are your greatest gifts. You inspire others through your idealism and generous spirit. Your broad perspective sees the big picture. Challenges - Avoid martyrdom and impracticality. Learn to complete projects and follow through on commitments.

### MATURITY NUMBER (1-9)
1: In your later years, you will increasingly value independence and self-reliance. A desire to lead and make your unique mark on the world will grow stronger. You may start new ventures or pursue long-held dreams with renewed determination.
2: In your later years, relationships and emotional fulfillment will take center stage. You will seek deeper connections and meaningful partnerships. Your wisdom in diplomacy and understanding human nature will make you a valued counselor.
3: In your later years, creative self-expression will become increasingly important. You will seek to express your authentic self through art, writing or communication. Your natural optimism and joy will radiate more strongly.
4: As you enter later life, you will notice a shift towards practicality, organisation and concern for material achievements. You will turn ideas into practical realities. A deep desire for material success and respect persists. Legacy-building and strengthening family bonds become priorities. Avoid becoming rigid or overly work-focused.
5: In your later years, freedom and adventure will remain important. You will seek new experiences and resist being tied down. Your adaptability will serve you well through life changes. Travel and learning keep your spirit young.
6: In your later years, love, family and community will be your greatest sources of fulfillment. You will take on a nurturing, wise elder role. Creating beauty and harmony in your environment becomes deeply satisfying.
7: As you mature, this number carries a philosophical and inherently wise energy. You will gradually let go of mundane aspects and expand mental horizons. Reading, contemplation and searching for Truths becomes central. Drawn to metaphysical subjects. Intuition sharpens. Need for privacy grows. Avoid excessive solitude.
8: In your later years, the desire for achievement and material security intensifies. You will be drawn to positions of power and influence. Financial planning and building lasting legacy become central concerns. Balance ambition with wisdom.
9: In your later years, humanitarian impulses and spiritual wisdom will come to full expression. You will be drawn to service, teaching and sharing your life wisdom. Letting go of the personal in favor of the universal brings deep peace.

### PERSONAL YEAR (1-9) with positive/negative results and luck percentages
1: Year of New Beginnings, Fresh Starts and Independence. 
Positive: New opportunities open up. Increased energy and motivation. Excellent for starting new projects, businesses or relationships. Seeds planted now will flourish. 
Negative: May feel restless and impatient. Risk of acting impulsively. Old structures may fall away causing temporary discomfort.
Luck %: M1=90%, M2=70%, M3=80%, M4=60%, M5=75%, M6=65%, M7=55%, M8=70%, M9=85%

2: Year of Cooperation, Relationships and Patience.
Positive: Relationships deepen and flourish. Good year for partnerships and collaborations. Intuition is heightened. Emotional healing occurs.
Negative: May feel overly sensitive or indecisive. Progress seems slow. Avoid confrontations and hasty decisions.
Luck %: M1=65%, M2=90%, M3=70%, M4=75%, M5=60%, M6=85%, M7=80%, M8=55%, M9=70%

3: Year of Creativity, Expression and Social Expansion.
Positive: Creative energy is high. Social life flourishes. Excellent for artistic projects, communication and networking. Joy and optimism abound.
Negative: Risk of scattering energy. May be superficial or avoid serious responsibilities. Watch spending.
Luck %: M1=80%, M2=70%, M3=90%, M4=65%, M5=75%, M6=70%, M7=60%, M8=55%, M9=85%

4: Year of Stability, Security and Hard Work.
Positive: Will keep you in illusion for first 2 months then develop practicality. You become very practical. A sense of security will develop. Time to set a routine and build a system. Be aware and take care of your health.
Negative: Low energy levels. Will feel pressurised. Days will go rigid and slow. You will be frustrated. Must do hard work to earn - cannot rely on luck.
Luck %: M1=100%, M2=75%, M3=70%, M4=85%, M5=60%, M6=80%, M7=65%, M8=90%, M9=55%

5: Year of Change, Freedom and Adventure.
Positive: Exciting changes and new opportunities. Travel and new experiences. Increased freedom and flexibility. Dynamic energy brings breakthroughs.
Negative: Instability and unpredictability. Difficulty maintaining routines. Risk of making hasty decisions. Scattered focus.
Luck %: M1=70%, M2=60%, M3=75%, M4=65%, M5=90%, M6=55%, M7=80%, M8=70%, M9=85%

6: Year of Love, Family and Responsibility.
Positive: Family relationships strengthen. Home improvements and beautification. Opportunities for healing relationships. Creative and artistic endeavors flourish.
Negative: Increased responsibilities and obligations. May feel burdened by demands of others. Avoid meddling in others affairs.
Luck %: M1=65%, M2=85%, M3=70%, M4=75%, M5=55%, M6=90%, M7=60%, M8=70%, M9=80%

7: Year of Reflection, Spirituality and Inner Growth.
Positive: Deep spiritual insights and personal growth. Excellent for study, research and self-discovery. Intuition is very strong. Inner wisdom develops.
Negative: May feel isolated or withdrawn. Material progress is slow. Avoid major financial decisions. Not a year for aggressive action.
Luck %: M1=55%, M2=80%, M3=65%, M4=70%, M5=75%, M6=60%, M7=90%, M8=65%, M9=85%

8: Year of Power, Achievement and Financial Growth.
Positive: Career advancement and financial opportunities. Increased authority and recognition. Excellent for business expansion and investments. Hard work brings substantial rewards.
Negative: Risk of overwork and burnout. Power struggles may arise. Avoid cutting corners or unethical shortcuts. Balance ambition with health.
Luck %: M1=75%, M2=60%, M3=65%, M4=85%, M5=70%, M6=75%, M7=55%, M8=90%, M9=70%

9: Year of Completion, Release and Transformation.
Positive: Completion of long cycles. Letting go brings liberation. Humanitarian work is rewarding. Wisdom and compassion grow. Preparation for new cycle ahead.
Negative: Endings can be painful. Must release what no longer serves. Avoid starting major new projects - this is a time of completion. Emotional intensity.
Luck %: M1=85%, M2=70%, M3=80%, M4=60%, M5=75%, M6=70%, M7=80%, M8=65%, M9=90%

### CAREER NUMEROLOGY
Generate for all Mulank (1-9) and Bhagyank (1-9) combinations. Use these exact examples:
M1+B4: General - Mulank 1 individuals are natural leaders and innovators. Bhagyank 4 brings stability, discipline and practical approach. Career Fields: Business Management, Financial Planning, Project Management, Administration, Real Estate. Strengths: leadership skills, practical approach, strong discipline. Challenges: flexibility in changing environments, learning to delegate.
M3+B7: General - Mulank 3 individuals are creative, expressive and communicative. Bhagyank 7 brings intuition, spirituality and analytical depth. Career Fields: Content Creation for Spirituality, Holistic Healing Practitioner, Spiritual Counselling, Creative Writing/Authorship, Media Production. Strengths: creative spirituality, intuitive problem solving, effective communication. Challenges: balancing practicality and idealism, managing emotional depth.
Generate the remaining 79 combinations in similar format.

### LO SHU GRID interpretations
For each digit 1-9, provide interpretation based on count (1 occurrence, 2 occurrences, 3+ occurrences):

1 (once): Self-confident, expressive and vocal. Good communication skills. Natural ability to connect with others.
1 (twice): Strong communicator but may sometimes overexplain. Good at influencing others through words.
1 (3+ times): Difficulty vocalizing thoughts despite strong opinions. May attract conflicts through speech. Tendency to overexplain. Hard to say no. Can become dependent on others.

2 (once): Balanced intuition and emotional sensitivity. Good family values and relationships.
2 (twice): Very family-oriented - family is everything. Highly intuitive with almost always correct instincts. Sensitive and emotionally driven.
2 (3+ times): Extremely sensitive and emotional. May be overly dependent on family. Strong psychic abilities but can be overwhelmed by emotions.

3 (once): Sharp-minded, creative and knowledgeable. Exemplary imagination. Learns fast and plans efficiently. May experience delay in success but gets there eventually. Both business and job suit equally.
3 (twice): Highly creative with strong intellectual capabilities. Excellent planner and executor of ideas.
3 (3+ times): Exceptional creativity and intelligence. Natural teacher and knowledge-sharer. May become impatient with slower minds.

4 (once): Practical and hardworking. Excellent hand-related skills like cooking, sewing, coding, playing instruments. Gets unique revolutionary ideas. Proficient in debates. Law is suitable career. Believes in multiple income sources. Dislikes grey areas.
4 (twice): Very practical and disciplined. Strong financial instincts and investment mindset.
4 (3+ times): Extremely hardworking but may become rigid. Exceptional practical skills. Must balance work with rest.

5 (once): Balanced personality. Good connector between different areas of life. Practical and adaptable.
5 (twice): Strong mediating abilities. Excellent at balancing opposing forces. Natural diplomat.
5 (3+ times): Extremely versatile but may lack direction. Exceptional communication skills. Needs to focus energy productively.

6 (once): Artistic sensibilities and appreciation for beauty. Caring and family-oriented. Good financial instincts.
6 (twice): Strong creative abilities and aesthetic sense. Very nurturing and family-devoted.
6 (3+ times): Exceptional artistic talent. Extremely family-focused. May neglect own needs for others. Strong healing abilities.

7 (once): Blessed with intuitive powers that guide down right path. Family and children supportive. Respects all relationships. Always learns from mistakes. Dissatisfaction and heartbreaks likely in one area. Spirituality will knock early.
7 (twice): Very spiritually inclined. Strong intuition and healing abilities. Deep bond with family.
7 (3+ times): Exceptional spiritual gifts. May feel caught between material and spiritual worlds. Powerful healer and mystic.

8 (once): Good financial awareness and practical wisdom. Learns valuable life lessons through hardships.
8 (twice): Strong financial acumen and business sense. Excellent at managing resources.
8 (3+ times): Exceptional material success potential. Very disciplined and ambitious. May become overly focused on material gain.

9 (once): Highly ambitious from early age with immense willpower. Kind and helps others selflessly. Prefers giving orders over taking them. Forgives but never forgets insults. Promised high energy for any task.
9 (twice): Very humanitarian and generous. Strong leadership qualities. High energy and ambition.
9 (3+ times): Enjoys being appreciated. Straightforward and very generous with humanitarian intentions. May overlook opinions of others. Needs to channel energy surges through physical activities.

### MISSING NUMBER impacts and exact remedies
1: No ego, low self-confidence, introverted, problems expressing experiences, face career problems. Remedy (Sunday): Donate Jaggery. Wear: Bloodstone + Tiger Eye bracelet. Chant: Om Shreem Suryay Namh. Yantra: Surya Yantra. Rudraksh: 1 Mukhi & 12 Mukhi.
2: Problems in love relations, lack of stability and patience, live in imaginations, lack of intuition and self-confidence. Remedy (Monday): Donate white things. Wear: Mother of Pearl + Howlite bracelet. Chant: Om shram shreem shraum sah chandramasaye namah. Yantra: Chandra Yantra. Rudraksh: 2 Mukhi.
3: Less grace of Guru and lord, problems in promotion and growth, lack of creative thinking, low self-confidence, easily distracted. Remedy (Thursday): Donate Yellow things. Wear: Natural Turquoise + Natural Amazonite bracelet. Chant: Om Gram greem groum sah gurave naman. Yantra: Guru Yantra. Rudraksh: 5 Mukhi.
4: Lack of financial stability and growth, lack of intuition power, struggle to achieve success, becomes directionless, weak thought power. Remedy (Saturday): Donate Black things and alcohol (to reduce its effect). Wear: Black Agate + 7 chakra bracelet. Chant: Om bhram bhreem bhroum sah rahave namah. Yantra: Rahu Yantra. Rudraksh: 5 Mukhi.
5: Lack of stability and self-confidence, health problems related to stomach and back pain, trouble starting work, loss in business, problem making own house. Remedy (Wednesday): Donate Green things, Ghee, study material, teach free of cost. Wear: Green Zade + Green Aventurian bracelet. Chant: Om bram breem broum sah budhaya Namah. Yantra: Buddh Yantra. Rudraksh: 10 Mukhi.
6: Lack of money and luxury life, struggle to achieve success, shortage of good friends, family support not available at right time, problems in love relations due to introverted nature. Remedy (Friday): Donate perfumes, cashew and cosmetics. Wear: Rose Quartz + Dragon Vein bracelet. Chant: Om dram dreem droum sah shukraya namah. Yantra: Shukra Yantra. Rudraksh: 9 Mukhi.
7: Hindrance in work and studies, no family support, no success despite effort, struggle more than success, mental disturbance. Remedy (Wednesday): Donate Black Clothes and Blanket. Wear: Cat's Eye + Azurite bracelet. Chant: Om shram shreem shroum sah ketave namah (7000 times in 25 days). Yantra: Ketu Yantra. Rudraksh: 9 Mukhi.
8: Difficulty making financial decisions, no perfection in work, lack of motivation and stability, life has lots of ups and downs, poor health and wealth. Remedy (Saturday): Donate Chayadan and Mustard Oil. Wear: Amethyst + Black Agate bracelet. Chant: Om Pram Preem Prom sah shanayshcharaya namah. Yantra: Shani Yantra. Rudraksh: 7 Mukhi.

## UI Design
- Color scheme: primary gold #f5a623, dark brown #8B4513, background cream #FFF8F0, accent #D4A017
- Elegant header with app name "✨ Numerology Report" 
- Simple one-page form: Full Name text input + Date of Birth date picker + large "Generate Report" button
- Show calculated numbers summary at top of report (Mulank, Bhagyank, etc. in a grid of badges)
- Each section as a card with gold left border accent and clear heading
- Lo Shu Grid as a proper 3x3 HTML table with numbers 4,9,2/3,5,7/8,1,6
  - Present numbers: gold background (#f5a623), bold, black text
  - Missing numbers: light grey (#e0e0e0), grey text
- Missing numbers section: each number as a collapsible or sub-card showing impact + full remedy
- "Download PDF" button at top and bottom of report (POST to /generate-pdf with name+dob)
- Fully mobile responsive with comfortable padding
- No technical jargon visible to user - just beautiful, clear report

## Flask Routes
- GET / → serve index.html
- POST /generate-report → accept {name, dob}, return JSON with all calculated numbers and text
- POST /generate-pdf → accept {name, dob}, return PDF file download

Make sure the PDF looks clean and professional with all sections included.
