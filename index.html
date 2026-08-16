import React, { useState, useEffect, useRef, useMemo } from "react";
import {
  Search, ShoppingCart, Heart, User, Menu, X, Star, ChevronDown, ChevronRight,
  ChevronLeft, SlidersHorizontal, Truck, ShieldCheck, RotateCcw, Plus, Minus,
  Trash2, Tag, CreditCard, MapPin, Package, Bell, LogOut, LayoutDashboard,
  BarChart3, Users, Image as ImageIcon, Check, CheckCircle2, Clock, Zap,
  Percent, Eye, ArrowRight, Facebook, Instagram, Twitter, Youtube, Mail,
  Phone, Grid, List, Edit3, PlusCircle, MoreVertical, Smartphone, Wallet,
  Building2, Banknote, ArrowLeft, ZoomIn, ChevronUp, Sparkles, TrendingUp,
  Settings, FolderTree, Ticket, LayoutTemplate, MessageSquare, Boxes
} from "lucide-react";

/* ============================================================
   SMARTPIK — DESIGN TOKENS
   Navy + electric teal + coral, warm-white surface.
   Display: Space Grotesk / Body: Inter
============================================================ */
const FONT_IMPORT = `@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600;700;800&display=swap');`;

const T = {
  navy: "#121B3A",
  navy2: "#1E2A55",
  navySoft: "#2A3868",
  teal: "#00C2A8",
  tealDark: "#00A691",
  coral: "#FF6452",
  coralSoft: "#FFEDE9",
  gold: "#F5A623",
  bg: "#F5F6FA",
  card: "#FFFFFF",
  ink: "#121627",
  sub: "#6B7280",
  line: "#E7E9F1",
};

/* ============================================================
   MOCK DATA
============================================================ */
const CATEGORIES = [
  { id: "electronics", name: "Electronics", icon: "📱", count: 214 },
  { id: "fashion", name: "Fashion", icon: "👗", count: 389 },
  { id: "footwear", name: "Footwear", icon: "👟", count: 156 },
  { id: "home", name: "Home & Kitchen", icon: "🏠", count: 172 },
  { id: "beauty", name: "Beauty & Care", icon: "💄", count: 98 },
  { id: "sports", name: "Sports & Fitness", icon: "🏋️", count: 121 },
  { id: "bags", name: "Bags & Luggage", icon: "🎒", count: 64 },
  { id: "audio", name: "Audio", icon: "🎧", count: 87 },
];

const BRANDS = ["SmartPik Basics", "Auralis", "Northline", "Verve", "Kadence", "Trailhead", "Lumière", "Coreform", "Pulse", "Wanderer"];

const IMG = {
  headphones: "https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=600&q=80&auto=format&fit=crop",
  headphones2: "https://images.unsplash.com/photo-1583394838336-acd977736f90?w=600&q=80&auto=format&fit=crop",
  sneakers: "https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=600&q=80&auto=format&fit=crop",
  sneakers2: "https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?w=600&q=80&auto=format&fit=crop",
  watch: "https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=600&q=80&auto=format&fit=crop",
  watch2: "https://images.unsplash.com/photo-1546868871-7041f2a55e12?w=600&q=80&auto=format&fit=crop",
  backpack: "https://images.unsplash.com/photo-1553062407-98eeb64c6a62?w=600&q=80&auto=format&fit=crop",
  sunglasses: "https://images.unsplash.com/photo-1572635196237-14b3f281503f?w=600&q=80&auto=format&fit=crop",
  perfume: "https://images.unsplash.com/photo-1541643600914-78b084683601?w=600&q=80&auto=format&fit=crop",
  laptop: "https://images.unsplash.com/photo-1496181133206-80ce9b88a853?w=600&q=80&auto=format&fit=crop",
  camera: "https://images.unsplash.com/photo-1516035069371-29a1b244cc32?w=600&q=80&auto=format&fit=crop",
  blender: "https://images.unsplash.com/photo-1570222094114-d054a817e56b?w=600&q=80&auto=format&fit=crop",
  jacket: "https://images.unsplash.com/photo-1551028719-00167b16eac5?w=600&q=80&auto=format&fit=crop",
  handbag: "https://images.unsplash.com/photo-1584917865442-de89df76afd3?w=600&q=80&auto=format&fit=crop",
  speaker: "https://images.unsplash.com/photo-1608043152269-423dbba4e7e1?w=600&q=80&auto=format&fit=crop",
  phone: "https://images.unsplash.com/photo-1592286927505-1def25115481?w=600&q=80&auto=format&fit=crop",
  skincare: "https://images.unsplash.com/photo-1620916566398-39f1143ab7be?w=600&q=80&auto=format&fit=crop",
  console: "https://images.unsplash.com/photo-1606813907291-d86efa9b94db?w=600&q=80&auto=format&fit=crop",
  kettle: "https://images.unsplash.com/photo-1585771724684-38269d6639fd?w=600&q=80&auto=format&fit=crop",
  yogamat: "https://images.unsplash.com/photo-1518611012118-696072aa579a?w=600&q=80&auto=format&fit=crop",
};

function pct(mrp, price) { return Math.round(((mrp - price) / mrp) * 100); }

const RAW_PRODUCTS = [
  { name: "AuralWave Pro Wireless Headphones", brand: "Auralis", cat: "audio", mrp: 8999, price: 5399, rating: 4.6, reviews: 1284, img: IMG.headphones, img2: IMG.headphones2, stock: 34, tag: "Best Seller" },
  { name: "Stratos Runner Knit Sneakers", brand: "Trailhead", cat: "footwear", mrp: 4499, price: 2699, rating: 4.4, reviews: 862, img: IMG.sneakers, img2: IMG.sneakers2, stock: 58, tag: "Trending" },
  { name: "Chrono Fit Pulse Smartwatch", brand: "Pulse", cat: "electronics", mrp: 12999, price: 8749, rating: 4.5, reviews: 2031, img: IMG.watch, img2: IMG.watch2, stock: 22, tag: "New" },
  { name: "Wanderer Urban Commuter Backpack", brand: "Wanderer", cat: "bags", mrp: 3299, price: 1979, rating: 4.7, reviews: 546, img: IMG.backpack, img2: IMG.backpack, stock: 71, tag: "Best Seller" },
  { name: "Coreform Polarized Aviators", brand: "Coreform", cat: "fashion", mrp: 2199, price: 1099, rating: 4.2, reviews: 318, img: IMG.sunglasses, img2: IMG.sunglasses, stock: 45, tag: "" },
  { name: "Lumière Eau de Parfum 50ml", brand: "Lumière", cat: "beauty", mrp: 3599, price: 2519, rating: 4.8, reviews: 940, img: IMG.perfume, img2: IMG.perfume, stock: 12, tag: "Trending" },
  { name: "Northline Air 14\" Ultrabook", brand: "Northline", cat: "electronics", mrp: 68999, price: 54999, rating: 4.5, reviews: 421, img: IMG.laptop, img2: IMG.laptop, stock: 9, tag: "New" },
  { name: "Verve StreetShot Mirrorless Camera", brand: "Verve", cat: "electronics", mrp: 45999, price: 36799, rating: 4.6, reviews: 267, img: IMG.camera, img2: IMG.camera, stock: 14, tag: "" },
  { name: "Kadence NutriBlend 900W Blender", brand: "Kadence", cat: "home", mrp: 4999, price: 2999, rating: 4.3, reviews: 703, img: IMG.blender, img2: IMG.blender, stock: 38, tag: "Deal" },
  { name: "Northline Storm Windbreaker Jacket", brand: "Northline", cat: "fashion", mrp: 3799, price: 2279, rating: 4.4, reviews: 389, img: IMG.jacket, img2: IMG.jacket, stock: 27, tag: "" },
  { name: "Lumière Signature Tote Handbag", brand: "Lumière", cat: "bags", mrp: 5499, price: 3849, rating: 4.6, reviews: 512, img: IMG.handbag, img2: IMG.handbag, stock: 19, tag: "Trending" },
  { name: "Pulse BassCore Bluetooth Speaker", brand: "Pulse", cat: "audio", mrp: 3999, price: 2399, rating: 4.5, reviews: 1102, img: IMG.speaker, img2: IMG.speaker, stock: 63, tag: "Best Seller" },
  { name: "SmartPik Nova X1 Smartphone", brand: "SmartPik Basics", cat: "electronics", mrp: 24999, price: 18749, rating: 4.4, reviews: 1890, img: IMG.phone, img2: IMG.phone, stock: 41, tag: "New" },
  { name: "Coreform DailyGlow Skincare Set", brand: "Coreform", cat: "beauty", mrp: 2799, price: 1959, rating: 4.7, reviews: 674, img: IMG.skincare, img2: IMG.skincare, stock: 52, tag: "Deal" },
  { name: "Pulse PlayZone Wireless Controller", brand: "Pulse", cat: "electronics", mrp: 5499, price: 3849, rating: 4.5, reviews: 445, img: IMG.console, img2: IMG.console, stock: 31, tag: "" },
  { name: "Kadence RapidBoil Electric Kettle", brand: "Kadence", cat: "home", mrp: 1999, price: 1199, rating: 4.3, reviews: 528, img: IMG.kettle, img2: IMG.kettle, stock: 66, tag: "Deal" },
  { name: "Trailhead FlexGrip Yoga Mat", brand: "Trailhead", cat: "sports", mrp: 1799, price: 999, rating: 4.6, reviews: 812, img: IMG.yogamat, img2: IMG.yogamat, stock: 84, tag: "Best Seller" },
  { name: "Verve TrailRunner Trekking Shoes", brand: "Verve", cat: "footwear", mrp: 3999, price: 2599, rating: 4.3, reviews: 291, img: IMG.sneakers2, img2: IMG.sneakers, stock: 40, tag: "" },
];

const PRODUCTS = RAW_PRODUCTS.map((p, i) => ({
  id: `SP-${1000 + i}`,
  ...p,
  discount: pct(p.mrp, p.price),
  colors: ["#121B3A", "#00C2A8", "#FF6452", "#E7E9F1"].slice(0, 2 + (i % 3)),
  sizes: p.cat === "footwear" ? ["UK 6", "UK 7", "UK 8", "UK 9", "UK 10"] : p.cat === "fashion" ? ["S", "M", "L", "XL"] : null,
  desc: `The ${p.name} is engineered for people who expect more from everyday gear — considered materials, a refined finish, and details that hold up to daily use. Designed by ${p.brand} and quality-checked before it ships from a SmartPik fulfillment center.`,
  specs: [
    ["Brand", p.brand], ["Category", CATEGORIES.find(c => c.id === p.cat)?.name || p.cat],
    ["Warranty", "1 Year SmartPik Assurance"], ["Model", `${p.brand.split(" ")[0].toUpperCase()}-${1000 + i}`],
    ["In the box", "1 Unit, User Guide, Warranty Card"],
  ],
}));

const REVIEW_NAMES = ["Ananya R.", "Rohan M.", "Priya K.", "Devansh S.", "Meera J.", "Kabir T.", "Ishita V.", "Arjun P."];
function makeReviews(seed) {
  const texts = [
    "Exceeded my expectations — build quality feels genuinely premium for the price.",
    "Delivery was quick and packaging was excellent. Product matches the photos exactly.",
    "Good value overall, though I wish it came in one more colour option.",
    "This is my second purchase from SmartPik — consistent quality every time.",
    "Works great day to day. Customer support was also very responsive when I had a question.",
  ];
  return Array.from({ length: 3 }).map((_, i) => ({
    name: REVIEW_NAMES[(seed + i) % REVIEW_NAMES.length],
    rating: [5, 4, 5, 4, 5][(seed + i) % 5],
    date: ["2 weeks ago", "1 month ago", "3 days ago", "2 months ago"][(seed + i) % 4],
    text: texts[(seed + i) % texts.length],
    verified: true,
  }));
}

const TESTIMONIALS = [
  { name: "Sanya Kapoor", role: "Verified Buyer", text: "SmartPik has become my default for anything I need in a hurry — fast delivery, easy returns, and prices that actually beat everyone else.", rating: 5 },
  { name: "Vikram Oberoi", role: "Verified Buyer", text: "The comparison tools and detailed specs made choosing a laptop so much easier. Genuinely useful, not just a gimmick.", rating: 5 },
  { name: "Fatima Sheikh", role: "Verified Buyer", text: "Returned a pair of shoes that didn't fit — refund was processed in two days, no questions asked.", rating: 4 },
  { name: "Aditya Rao", role: "Verified Buyer", text: "Clean app, honest discounts, and the order tracking is accurate down to the hour. Highly recommend.", rating: 5 },
];

/* ============================================================
   SMALL SHARED COMPONENTS
============================================================ */
function Stars({ rating, size = 14 }) {
  const full = Math.floor(rating);
  const half = rating - full >= 0.5;
  return (
    <span style={{ display: "inline-flex", gap: 1, alignItems: "center" }}>
      {Array.from({ length: 5 }).map((_, i) => (
        <Star
          key={i}
          size={size}
          fill={i < full || (i === full && half) ? T.gold : "none"}
          color={i < full || (i === full && half) ? T.gold : T.line}
          strokeWidth={1.5}
        />
      ))}
    </span>
  );
}

function Price({ price, mrp, size = "md" }) {
  const s = size === "lg" ? { p: 26, m: 15 } : size === "sm" ? { p: 14, m: 11 } : { p: 17, m: 12.5 };
  const d = pct(mrp, price);
  return (
    <div style={{ display: "flex", alignItems: "baseline", gap: 8, flexWrap: "wrap" }}>
      <span style={{ fontFamily: "'Space Grotesk',sans-serif", fontWeight: 700, fontSize: s.p, color: T.ink }}>₹{price.toLocaleString("en-IN")}</span>
      {mrp > price && <span style={{ fontSize: s.m, color: T.sub, textDecoration: "line-through" }}>₹{mrp.toLocaleString("en-IN")}</span>}
      {mrp > price && <span style={{ fontSize: s.m, color: T.teal, fontWeight: 700 }}>{d}% off</span>}
    </div>
  );
}

function Badge({ children, tone = "teal" }) {
  const tones = {
    teal: { bg: "#E3FBF7", fg: T.tealDark },
    coral: { bg: T.coralSoft, fg: "#D6472F" },
    navy: { bg: "#EAEDF7", fg: T.navy2 },
    gold: { bg: "#FDF3E0", fg: "#B9770E" },
  };
  const c = tones[tone];
  return (
    <span style={{ background: c.bg, color: c.fg, fontSize: 11, fontWeight: 700, padding: "3px 9px", borderRadius: 999, letterSpacing: ".02em" }}>
      {children}
    </span>
  );
}

function IconBtn({ icon: Icon, onClick, active, count, label, size = 20 }) {
  return (
    <button
      onClick={onClick}
      aria-label={label}
      style={{
        position: "relative", background: "none", border: "none", cursor: "pointer",
        color: active ? T.teal : T.navy, padding: 8, borderRadius: 10, display: "flex",
        alignItems: "center", justifyContent: "center", transition: "background .15s",
      }}
      onMouseEnter={e => e.currentTarget.style.background = "#F0F1F6"}
      onMouseLeave={e => e.currentTarget.style.background = "transparent"}
    >
      <Icon size={size} strokeWidth={1.8} fill={active ? T.teal : "none"} />
      {count > 0 && (
        <span style={{
          position: "absolute", top: 0, right: 0, background: T.coral, color: "#fff",
          fontSize: 10, fontWeight: 700, borderRadius: 999, minWidth: 16, height: 16,
          display: "flex", alignItems: "center", justifyContent: "center", padding: "0 3px",
        }}>{count}</span>
      )}
    </button>
  );
}

function Btn({ children, onClick, variant = "primary", full, size = "md", icon: Icon, disabled, type = "button" }) {
  const sizes = { sm: "8px 14px", md: "12px 20px", lg: "15px 28px" };
  const fs = { sm: 13, md: 14.5, lg: 16 };
  const styles = {
    primary: { background: T.navy, color: "#fff", border: `1px solid ${T.navy}` },
    accent: { background: T.teal, color: "#fff", border: `1px solid ${T.teal}` },
    coral: { background: T.coral, color: "#fff", border: `1px solid ${T.coral}` },
    outline: { background: "transparent", color: T.navy, border: `1.5px solid ${T.navy}` },
    ghost: { background: "#F0F1F6", color: T.navy, border: "1px solid transparent" },
    white: { background: "#fff", color: T.navy, border: `1px solid ${T.line}` },
  };
  return (
    <button
      type={type}
      disabled={disabled}
      onClick={onClick}
      style={{
        ...styles[variant], padding: sizes[size], fontSize: fs[size], fontWeight: 700,
        borderRadius: 11, cursor: disabled ? "not-allowed" : "pointer", opacity: disabled ? 0.5 : 1,
        width: full ? "100%" : "auto", display: "inline-flex", alignItems: "center",
        justifyContent: "center", gap: 8, transition: "transform .12s, box-shadow .12s",
        fontFamily: "'Inter',sans-serif", whiteSpace: "nowrap",
      }}
      onMouseEnter={e => { if (!disabled) { e.currentTarget.style.transform = "translateY(-1px)"; e.currentTarget.style.boxShadow = "0 6px 16px rgba(18,27,58,.14)"; } }}
      onMouseLeave={e => { e.currentTarget.style.transform = "translateY(0)"; e.currentTarget.style.boxShadow = "none"; }}
    >
      {Icon && <Icon size={16} />}
      {children}
    </button>
  );
}

function SectionHead({ eyebrow, title, action, onAction }) {
  return (
    <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-end", marginBottom: 22, gap: 12, flexWrap: "wrap" }}>
      <div>
        {eyebrow && <div style={{ color: T.teal, fontWeight: 700, fontSize: 12.5, letterSpacing: ".08em", textTransform: "uppercase", marginBottom: 6 }}>{eyebrow}</div>}
        <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: "clamp(22px,3vw,30px)", margin: 0, color: T.ink, fontWeight: 700 }}>{title}</h2>
      </div>
      {action && (
        <button onClick={onAction} style={{ background: "none", border: "none", cursor: "pointer", color: T.navy2, fontWeight: 700, fontSize: 14, display: "flex", alignItems: "center", gap: 4 }}>
          {action} <ChevronRight size={16} />
        </button>
      )}
    </div>
  );
}

/* ============================================================
   PRODUCT CARD
============================================================ */
function ProductCard({ p, onOpen, onAddCart, onBuyNow, onToggleWish, wished }) {
  const [hover, setHover] = useState(false);
  return (
    <div
      onMouseEnter={() => setHover(true)}
      onMouseLeave={() => setHover(false)}
      style={{
        background: T.card, borderRadius: 16, border: `1px solid ${T.line}`, overflow: "hidden",
        display: "flex", flexDirection: "column", transition: "box-shadow .2s, transform .2s",
        boxShadow: hover ? "0 16px 32px rgba(18,27,58,.12)" : "0 1px 2px rgba(18,27,58,.04)",
        transform: hover ? "translateY(-4px)" : "translateY(0)", cursor: "pointer", height: "100%",
      }}
    >
      <div style={{ position: "relative", aspectRatio: "1/1", overflow: "hidden", background: "#F0F1F6" }} onClick={() => onOpen(p)}>
        <img src={hover ? p.img2 : p.img} alt={p.name} style={{ width: "100%", height: "100%", objectFit: "cover", transition: "transform .4s", transform: hover ? "scale(1.06)" : "scale(1)" }} />
        <div style={{ position: "absolute", top: 10, left: 10, display: "flex", gap: 6, flexDirection: "column", alignItems: "flex-start" }}>
          {p.tag && <Badge tone={p.tag === "Deal" ? "coral" : p.tag === "New" ? "gold" : "teal"}>{p.tag}</Badge>}
          <Badge tone="navy">{p.discount}% OFF</Badge>
        </div>
        <button
          onClick={(e) => { e.stopPropagation(); onToggleWish(p.id); }}
          style={{
            position: "absolute", top: 10, right: 10, background: "rgba(255,255,255,.92)", border: "none",
            width: 34, height: 34, borderRadius: "50%", display: "flex", alignItems: "center", justifyContent: "center", cursor: "pointer",
            boxShadow: "0 2px 6px rgba(0,0,0,.12)",
          }}
        >
          <Heart size={16} fill={wished ? T.coral : "none"} color={wished ? T.coral : T.navy} strokeWidth={1.8} />
        </button>
        {p.stock < 15 && (
          <div style={{ position: "absolute", bottom: 0, left: 0, right: 0, background: "rgba(18,27,58,.85)", color: "#fff", fontSize: 11, fontWeight: 600, textAlign: "center", padding: "5px 0" }}>
            Only {p.stock} left
          </div>
        )}
      </div>
      <div style={{ padding: "13px 14px 15px", display: "flex", flexDirection: "column", gap: 6, flex: 1 }} onClick={() => onOpen(p)}>
        <div style={{ fontSize: 11.5, color: T.sub, fontWeight: 600, textTransform: "uppercase", letterSpacing: ".03em" }}>{p.brand}</div>
        <div style={{ fontSize: 14.5, fontWeight: 600, color: T.ink, lineHeight: 1.35, minHeight: 38, display: "-webkit-box", WebkitLineClamp: 2, WebkitBoxOrient: "vertical", overflow: "hidden" }}>{p.name}</div>
        <div style={{ display: "flex", alignItems: "center", gap: 6 }}>
          <Stars rating={p.rating} size={13} />
          <span style={{ fontSize: 12.5, color: T.sub }}>{p.rating} ({p.reviews.toLocaleString("en-IN")})</span>
        </div>
        <div style={{ marginTop: 2 }}><Price price={p.price} mrp={p.mrp} /></div>
        <div style={{ display: "flex", gap: 8, marginTop: 10 }} onClick={(e) => e.stopPropagation()}>
          <Btn size="sm" variant="ghost" full onClick={() => onAddCart(p)}>Add to Cart</Btn>
          <Btn size="sm" variant="accent" full onClick={() => onBuyNow(p)}>Buy Now</Btn>
        </div>
      </div>
    </div>
  );
}

/* ============================================================
   NAVBAR
============================================================ */
function Navbar({ nav, cartCount, wishCount, searchQ, setSearchQ, onSearchSubmit, onLogoClick }) {
  const [menuOpen, setMenuOpen] = useState(false);
  const [catOpen, setCatOpen] = useState(false);
  const [scrolled, setScrolled] = useState(false);
  useEffect(() => {
    const h = () => setScrolled(window.scrollY > 8);
    window.addEventListener("scroll", h);
    return () => window.removeEventListener("scroll", h);
  }, []);
  return (
    <div style={{ position: "sticky", top: 0, zIndex: 100 }}>
      <div style={{ background: T.navy, color: "#cfd5ea", fontSize: 12.5, padding: "6px 0", display: window.innerWidth < 640 ? "none" : "block" }}>
        <div style={{ maxWidth: 1280, margin: "0 auto", padding: "0 24px", display: "flex", justifyContent: "space-between" }}>
          <span>Free delivery on orders above ₹499 · Easy 7-day returns</span>
          <span style={{ display: "flex", gap: 18 }}>
            <span>Track Order</span><span>Help Center</span><span>Sell on SmartPik</span>
          </span>
        </div>
      </div>
      <div style={{ background: "#fff", borderBottom: `1px solid ${T.line}`, boxShadow: scrolled ? "0 4px 16px rgba(18,27,58,.06)" : "none", transition: "box-shadow .2s" }}>
        <div style={{ maxWidth: 1280, margin: "0 auto", padding: "12px 20px", display: "flex", alignItems: "center", gap: 18 }}>
          <button onClick={() => setMenuOpen(true)} style={{ display: "none", background: "none", border: "none" }} className="mobile-only-btn">
            <Menu size={24} />
          </button>
          <div onClick={onLogoClick} style={{ display: "flex", alignItems: "center", gap: 8, cursor: "pointer", flexShrink: 0 }}>
            <div style={{ width: 36, height: 36, borderRadius: 10, background: `linear-gradient(135deg, ${T.teal}, ${T.navy})`, display: "flex", alignItems: "center", justifyContent: "center" }}>
              <Zap size={19} color="#fff" fill="#fff" />
            </div>
            <span style={{ fontFamily: "'Space Grotesk',sans-serif", fontWeight: 700, fontSize: 21, color: T.ink }}>SmartPik</span>
          </div>

          <div style={{ position: "relative" }}>
            <button onMouseEnter={() => setCatOpen(true)} onMouseLeave={() => setCatOpen(false)}
              style={{ display: "flex", alignItems: "center", gap: 5, background: "none", border: "none", fontWeight: 600, fontSize: 14.5, color: T.navy, cursor: "pointer", padding: "8px 4px" }}>
              Categories <ChevronDown size={15} />
            </button>
            {catOpen && (
              <div onMouseEnter={() => setCatOpen(true)} onMouseLeave={() => setCatOpen(false)}
                style={{ position: "absolute", top: "100%", left: 0, background: "#fff", boxShadow: "0 16px 40px rgba(18,27,58,.16)", borderRadius: 14, padding: 10, width: 260, display: "grid", gridTemplateColumns: "1fr 1fr", gap: 2 }}>
                {CATEGORIES.map(c => (
                  <div key={c.id} onClick={() => nav("listing", { category: c.id })}
                    style={{ display: "flex", alignItems: "center", gap: 8, padding: "9px 10px", borderRadius: 9, cursor: "pointer", fontSize: 13.5 }}
                    onMouseEnter={e => e.currentTarget.style.background = "#F5F6FA"} onMouseLeave={e => e.currentTarget.style.background = "transparent"}>
                    <span>{c.icon}</span><span style={{ fontWeight: 500 }}>{c.name}</span>
                  </div>
                ))}
              </div>
            )}
          </div>

          <form onSubmit={(e) => { e.preventDefault(); onSearchSubmit(); }} style={{ flex: 1, maxWidth: 620, display: "flex" }}>
            <div style={{ display: "flex", alignItems: "center", width: "100%", background: T.bg, border: `1.5px solid ${T.line}`, borderRadius: 12, padding: "0 6px 0 14px" }}>
              <Search size={17} color={T.sub} />
              <input
                value={searchQ}
                onChange={e => setSearchQ(e.target.value)}
                placeholder="Search products, brands and categories"
                style={{ flex: 1, border: "none", background: "transparent", padding: "10px 10px", outline: "none", fontSize: 14, fontFamily: "'Inter',sans-serif" }}
              />
              <Btn size="sm" variant="accent" type="submit">Search</Btn>
            </div>
          </form>

          <div style={{ display: "flex", alignItems: "center", gap: 4, flexShrink: 0 }}>
            <IconBtn icon={User} onClick={() => nav("account")} label="Account" />
            <IconBtn icon={Heart} onClick={() => nav("wishlist")} count={wishCount} label="Wishlist" />
            <IconBtn icon={ShoppingCart} onClick={() => nav("cart")} count={cartCount} label="Cart" />
          </div>
        </div>
      </div>

      {menuOpen && (
        <div style={{ position: "fixed", inset: 0, background: "rgba(18,27,58,.5)", zIndex: 200 }} onClick={() => setMenuOpen(false)}>
          <div onClick={e => e.stopPropagation()} style={{ background: "#fff", width: 280, height: "100%", padding: 20 }}>
            <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 20 }}>
              <span style={{ fontFamily: "'Space Grotesk',sans-serif", fontWeight: 700, fontSize: 19 }}>SmartPik</span>
              <X onClick={() => setMenuOpen(false)} style={{ cursor: "pointer" }} />
            </div>
            {CATEGORIES.map(c => (
              <div key={c.id} onClick={() => { nav("listing", { category: c.id }); setMenuOpen(false); }} style={{ padding: "12px 4px", borderBottom: `1px solid ${T.line}`, fontSize: 15, cursor: "pointer" }}>{c.icon} {c.name}</div>
            ))}
          </div>
        </div>
      )}
    </div>
  );
}

/* ============================================================
   COUNTDOWN (signature interactive element for deals)
============================================================ */
function useCountdown(hoursFromNow) {
  const target = useRef(Date.now() + hoursFromNow * 3600 * 1000);
  const [left, setLeft] = useState(target.current - Date.now());
  useEffect(() => {
    const id = setInterval(() => setLeft(Math.max(0, target.current - Date.now())), 1000);
    return () => clearInterval(id);
  }, []);
  const h = Math.floor(left / 3600000);
  const m = Math.floor((left % 3600000) / 60000);
  const s = Math.floor((left % 60000) / 1000);
  return { h, m, s };
}

function CountdownPill() {
  const { h, m, s } = useCountdown(11.4);
  const pad = n => String(n).padStart(2, "0");
  return (
    <div style={{ display: "inline-flex", alignItems: "center", gap: 6, background: "rgba(255,255,255,.14)", padding: "7px 12px", borderRadius: 999, fontSize: 13, fontWeight: 700, color: "#fff" }}>
      <Clock size={14} /> Deal ends in {pad(h)}:{pad(m)}:{pad(s)}
    </div>
  );
}

/* ============================================================
   HOME PAGE
============================================================ */
function Hero({ nav }) {
  const cards = [PRODUCTS[0], PRODUCTS[2], PRODUCTS[10]];
  return (
    <div style={{ position: "relative", background: `linear-gradient(120deg, ${T.navy} 0%, ${T.navy2} 55%, #24316a 100%)`, overflow: "hidden" }}>
      <div style={{ position: "absolute", width: 480, height: 480, borderRadius: "50%", background: T.teal, opacity: 0.18, filter: "blur(60px)", top: -160, right: -100 }} />
      <div style={{ maxWidth: 1280, margin: "0 auto", padding: "56px 24px 76px", display: "grid", gridTemplateColumns: "1.1fr 0.9fr", gap: 40, position: "relative", alignItems: "center" }} className="hero-grid">
        <div>
          <div style={{ display: "inline-flex", alignItems: "center", gap: 8, background: "rgba(0,194,168,.16)", color: T.teal, padding: "6px 13px", borderRadius: 999, fontSize: 12.5, fontWeight: 700, marginBottom: 20 }}>
            <Sparkles size={14} /> SEASON SALE · UP TO 60% OFF
          </div>
          <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: "clamp(34px,4.6vw,56px)", color: "#fff", lineHeight: 1.06, fontWeight: 700, margin: "0 0 16px" }}>
            Smart Choices.<br /><span style={{ color: T.teal }}>Better Shopping.</span>
          </h1>
          <p style={{ color: "#B9C1DE", fontSize: 16.5, maxWidth: 460, lineHeight: 1.6, marginBottom: 26 }}>
            Curated electronics, fashion, and home essentials — compared, rated, and delivered fast. Everything you need, nothing you don't.
          </p>
          <div style={{ display: "flex", gap: 14, flexWrap: "wrap", alignItems: "center" }}>
            <Btn variant="accent" size="lg" icon={ArrowRight} onClick={() => nav("listing", {})}>Shop Now</Btn>
            <CountdownPill />
          </div>
        </div>
        <div style={{ position: "relative", height: 380 }} className="hero-cards">
          {cards.map((p, i) => (
            <div key={p.id} onClick={() => nav("product", { id: p.id })}
              style={{
                position: "absolute", width: 190, background: "#fff", borderRadius: 16, padding: 12, cursor: "pointer",
                boxShadow: "0 24px 48px rgba(0,0,0,.35)", transition: "transform .3s",
                top: [10, 130, 250][i], left: [40, 210, 20][i], transform: `rotate(${[-6, 4, -3][i]}deg)`,
              }}
              onMouseEnter={e => e.currentTarget.style.transform = "rotate(0deg) scale(1.05)"}
              onMouseLeave={e => e.currentTarget.style.transform = `rotate(${[-6, 4, -3][i]}deg) scale(1)`}
            >
              <img src={p.img} alt={p.name} style={{ width: "100%", height: 100, objectFit: "cover", borderRadius: 10, marginBottom: 8 }} />
              <div style={{ fontSize: 12, fontWeight: 600, color: T.ink, lineHeight: 1.3, marginBottom: 4 }}>{p.name.split(" ").slice(0, 3).join(" ")}</div>
              <Price price={p.price} mrp={p.mrp} size="sm" />
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function CategoryStrip({ nav }) {
  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "48px 24px 8px" }}>
      <SectionHead eyebrow="Browse" title="Featured Categories" />
      <div style={{ display: "grid", gridTemplateColumns: "repeat(8,1fr)", gap: 14 }} className="cat-grid">
        {CATEGORIES.map(c => (
          <div key={c.id} onClick={() => nav("listing", { category: c.id })}
            style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: "22px 10px", textAlign: "center", cursor: "pointer", transition: "transform .15s, box-shadow .15s" }}
            onMouseEnter={e => { e.currentTarget.style.transform = "translateY(-3px)"; e.currentTarget.style.boxShadow = "0 12px 24px rgba(18,27,58,.1)"; }}
            onMouseLeave={e => { e.currentTarget.style.transform = "translateY(0)"; e.currentTarget.style.boxShadow = "none"; }}>
            <div style={{ fontSize: 30, marginBottom: 8 }}>{c.icon}</div>
            <div style={{ fontWeight: 700, fontSize: 13, color: T.ink }}>{c.name}</div>
            <div style={{ fontSize: 11.5, color: T.sub }}>{c.count} items</div>
          </div>
        ))}
      </div>
    </div>
  );
}

function ProductRow({ title, eyebrow, items, cartActions, nav }) {
  const scroller = useRef(null);
  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "40px 24px 8px" }}>
      <SectionHead eyebrow={eyebrow} title={title} action="View all" onAction={() => nav("listing", {})} />
      <div style={{ position: "relative" }}>
        <div ref={scroller} style={{ display: "flex", gap: 16, overflowX: "auto", paddingBottom: 8, scrollBehavior: "smooth" }} className="hide-scrollbar">
          {items.map(p => (
            <div key={p.id} style={{ minWidth: 232, maxWidth: 232 }}>
              <ProductCard p={p} {...cartActions} onOpen={(pp) => nav("product", { id: pp.id })} />
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function DealsBanner({ nav }) {
  return (
    <div style={{ maxWidth: 1280, margin: "44px auto 0", padding: "0 24px" }}>
      <div style={{ background: `linear-gradient(115deg, ${T.coral}, #FF8A67)`, borderRadius: 22, padding: "34px 36px", display: "flex", justifyContent: "space-between", alignItems: "center", flexWrap: "wrap", gap: 20 }}>
        <div>
          <div style={{ color: "#fff", fontWeight: 700, fontSize: 12.5, letterSpacing: ".08em", textTransform: "uppercase", opacity: .9, marginBottom: 8 }}>Special Deals</div>
          <h3 style={{ fontFamily: "'Space Grotesk',sans-serif", color: "#fff", fontSize: 28, margin: "0 0 10px", fontWeight: 700 }}>Flash Sale — up to 60% off audio &amp; wearables</h3>
          <CountdownPill />
        </div>
        <Btn variant="white" size="lg" icon={ArrowRight} onClick={() => nav("listing", { category: "electronics" })}>Grab the Deal</Btn>
      </div>
    </div>
  );
}

function Testimonials() {
  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "48px 24px 8px" }}>
      <SectionHead eyebrow="Community" title="What customers are saying" />
      <div style={{ display: "grid", gridTemplateColumns: "repeat(4,1fr)", gap: 16 }} className="testi-grid">
        {TESTIMONIALS.map((t, i) => (
          <div key={i} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 20 }}>
            <Stars rating={t.rating} size={14} />
            <p style={{ fontSize: 13.8, color: T.ink, lineHeight: 1.6, margin: "12px 0 16px" }}>"{t.text}"</p>
            <div style={{ display: "flex", alignItems: "center", gap: 10 }}>
              <div style={{ width: 34, height: 34, borderRadius: "50%", background: T.navySoft, color: "#fff", display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 700, fontSize: 13 }}>{t.name[0]}</div>
              <div>
                <div style={{ fontWeight: 700, fontSize: 13 }}>{t.name}</div>
                <div style={{ fontSize: 11.5, color: T.sub }}>{t.role}</div>
              </div>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

function Newsletter() {
  const [email, setEmail] = useState("");
  const [sent, setSent] = useState(false);
  return (
    <div style={{ maxWidth: 1280, margin: "48px auto 0", padding: "0 24px" }}>
      <div style={{ background: T.navy, borderRadius: 22, padding: "40px 36px", textAlign: "center" }}>
        <h3 style={{ fontFamily: "'Space Grotesk',sans-serif", color: "#fff", fontSize: 26, margin: "0 0 8px" }}>Get 10% off your first order</h3>
        <p style={{ color: "#B9C1DE", marginBottom: 20, fontSize: 14.5 }}>Subscribe for early access to deals, new arrivals, and restocks.</p>
        {sent ? (
          <div style={{ color: T.teal, fontWeight: 700, display: "flex", justifyContent: "center", gap: 8, alignItems: "center" }}><CheckCircle2 size={18} /> Subscribed — check your inbox!</div>
        ) : (
          <form onSubmit={e => { e.preventDefault(); if (email) setSent(true); }} style={{ display: "flex", gap: 10, maxWidth: 420, margin: "0 auto" }}>
            <input required type="email" value={email} onChange={e => setEmail(e.target.value)} placeholder="you@email.com"
              style={{ flex: 1, padding: "13px 16px", borderRadius: 11, border: "none", outline: "none", fontSize: 14 }} />
            <Btn variant="accent" type="submit">Subscribe</Btn>
          </form>
        )}
      </div>
    </div>
  );
}

function Footer({ nav }) {
  return (
    <footer style={{ background: "#0D1330", color: "#9BA4C4", marginTop: 60 }}>
      <div style={{ maxWidth: 1280, margin: "0 auto", padding: "52px 24px 24px", display: "grid", gridTemplateColumns: "1.4fr 1fr 1fr 1fr 1.2fr", gap: 32 }} className="footer-grid">
        <div>
          <div style={{ display: "flex", alignItems: "center", gap: 8, marginBottom: 14 }}>
            <div style={{ width: 32, height: 32, borderRadius: 9, background: `linear-gradient(135deg, ${T.teal}, ${T.navy2})`, display: "flex", alignItems: "center", justifyContent: "center" }}><Zap size={16} color="#fff" fill="#fff" /></div>
            <span style={{ fontFamily: "'Space Grotesk',sans-serif", fontWeight: 700, fontSize: 18, color: "#fff" }}>SmartPik</span>
          </div>
          <p style={{ fontSize: 13, lineHeight: 1.7, maxWidth: 260 }}>Smart Choices. Better Shopping. Curated products, transparent pricing, and dependable delivery — all in one place.</p>
          <div style={{ display: "flex", gap: 10, marginTop: 16 }}>
            {[Facebook, Instagram, Twitter, Youtube].map((I, i) => (
              <div key={i} style={{ width: 32, height: 32, borderRadius: 8, background: "rgba(255,255,255,.06)", display: "flex", alignItems: "center", justifyContent: "center", cursor: "pointer" }}><I size={15} /></div>
            ))}
          </div>
        </div>
        {[
          { h: "Shop", items: ["New Arrivals", "Best Sellers", "Special Deals", "All Categories"] },
          { h: "Support", items: ["Help Center", "Track Order", "Returns & Refunds", "Shipping Info"] },
          { h: "Company", items: ["About SmartPik", "Careers", "Press", "Sell on SmartPik"] },
        ].map((col, i) => (
          <div key={i}>
            <div style={{ color: "#fff", fontWeight: 700, fontSize: 13.5, marginBottom: 14 }}>{col.h}</div>
            {col.items.map(it => <div key={it} style={{ fontSize: 13, marginBottom: 10, cursor: "pointer" }}>{it}</div>)}
          </div>
        ))}
        <div>
          <div style={{ color: "#fff", fontWeight: 700, fontSize: 13.5, marginBottom: 14 }}>Contact</div>
          <div style={{ fontSize: 13, marginBottom: 10, display: "flex", gap: 8 }}><Mail size={15} /> support@smartpik.com</div>
          <div style={{ fontSize: 13, marginBottom: 10, display: "flex", gap: 8 }}><Phone size={15} /> 1800-123-4567</div>
          <div style={{ display: "flex", gap: 8, marginTop: 14 }}>
            <button onClick={() => nav("admin")} style={{ background: "rgba(255,255,255,.08)", color: "#cfd5ea", border: "none", padding: "8px 12px", borderRadius: 8, fontSize: 12, cursor: "pointer" }}>Admin Dashboard →</button>
          </div>
        </div>
      </div>
      <div style={{ borderTop: "1px solid rgba(255,255,255,.08)", padding: "18px 24px", textAlign: "center", fontSize: 12.5 }}>
        © 2026 SmartPik Retail Pvt. Ltd. All rights reserved. · Prototype UI — payments &amp; auth to be connected to live services.
      </div>
    </footer>
  );
}

function HomePage({ nav, cartActions }) {
  const bestSellers = PRODUCTS.filter(p => p.tag === "Best Seller");
  const trending = PRODUCTS.filter(p => p.tag === "Trending" || p.tag === "");
  const newArrivals = PRODUCTS.filter(p => p.tag === "New");
  return (
    <div>
      <Hero nav={nav} />
      <CategoryStrip nav={nav} />
      <ProductRow eyebrow="Hot right now" title="Trending Products" items={trending.slice(0, 8)} cartActions={cartActions} nav={nav} />
      <ProductRow eyebrow="Customer favorites" title="Best Sellers" items={bestSellers.concat(PRODUCTS.slice(0, 3))} cartActions={cartActions} nav={nav} />
      <DealsBanner nav={nav} />
      <ProductRow eyebrow="Just landed" title="New Arrivals" items={newArrivals.concat(PRODUCTS.slice(4, 7))} cartActions={cartActions} nav={nav} />
      <Testimonials />
      <Newsletter />
    </div>
  );
}

/* ============================================================
   PRODUCT LISTING PAGE
============================================================ */
function ListingPage({ nav, params, cartActions, wishlist }) {
  const [filters, setFilters] = useState({
    category: params.category || "all", brands: [], maxPrice: 70000, minRating: 0, minDiscount: 0, inStockOnly: false,
  });
  const [sortBy, setSortBy] = useState("popularity");
  const [view, setView] = useState("grid");
  const [showFilters, setShowFilters] = useState(true);
  const [query, setQuery] = useState(params.q || "");

  useEffect(() => { setFilters(f => ({ ...f, category: params.category || "all" })); setQuery(params.q || ""); }, [params.category, params.q]);

  const filtered = useMemo(() => {
    let list = PRODUCTS.filter(p => {
      if (filters.category !== "all" && p.cat !== filters.category) return false;
      if (filters.brands.length && !filters.brands.includes(p.brand)) return false;
      if (p.price > filters.maxPrice) return false;
      if (p.rating < filters.minRating) return false;
      if (p.discount < filters.minDiscount) return false;
      if (filters.inStockOnly && p.stock <= 0) return false;
      if (query && !(p.name.toLowerCase().includes(query.toLowerCase()) || p.brand.toLowerCase().includes(query.toLowerCase()))) return false;
      return true;
    });
    switch (sortBy) {
      case "price-asc": list.sort((a, b) => a.price - b.price); break;
      case "price-desc": list.sort((a, b) => b.price - a.price); break;
      case "newest": list = [...list].reverse(); break;
      default: list.sort((a, b) => b.reviews - a.reviews);
    }
    return list;
  }, [filters, sortBy, query]);

  const toggleBrand = (b) => setFilters(f => ({ ...f, brands: f.brands.includes(b) ? f.brands.filter(x => x !== b) : [...f.brands, b] }));

  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "24px 20px 60px" }}>
      <div style={{ fontSize: 13, color: T.sub, marginBottom: 14, display: "flex", alignItems: "center", gap: 6 }}>
        <span onClick={() => nav("home")} style={{ cursor: "pointer" }}>Home</span> <ChevronRight size={13} />
        <span style={{ color: T.ink, fontWeight: 600 }}>{filters.category === "all" ? "All Products" : CATEGORIES.find(c => c.id === filters.category)?.name}</span>
      </div>

      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 18, flexWrap: "wrap", gap: 10 }}>
        <div>
          <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 26, margin: 0 }}>
            {query ? `Results for "${query}"` : filters.category === "all" ? "All Products" : CATEGORIES.find(c => c.id === filters.category)?.name}
          </h1>
          <div style={{ fontSize: 13.5, color: T.sub, marginTop: 4 }}>{filtered.length} products found</div>
        </div>
        <div style={{ display: "flex", gap: 10, alignItems: "center" }}>
          <button onClick={() => setShowFilters(s => !s)} style={{ display: "flex", alignItems: "center", gap: 6, background: "#fff", border: `1px solid ${T.line}`, padding: "9px 14px", borderRadius: 10, fontSize: 13.5, fontWeight: 600, cursor: "pointer" }} className="filter-toggle-btn">
            <SlidersHorizontal size={15} /> Filters
          </button>
          <select value={sortBy} onChange={e => setSortBy(e.target.value)} style={{ padding: "9px 12px", borderRadius: 10, border: `1px solid ${T.line}`, fontSize: 13.5, background: "#fff", fontWeight: 600 }}>
            <option value="popularity">Sort: Popularity</option>
            <option value="price-asc">Price: Low to High</option>
            <option value="price-desc">Price: High to Low</option>
            <option value="newest">Newest</option>
          </select>
          <div style={{ display: "flex", border: `1px solid ${T.line}`, borderRadius: 10, overflow: "hidden" }}>
            <button onClick={() => setView("grid")} style={{ background: view === "grid" ? T.navy : "#fff", color: view === "grid" ? "#fff" : T.navy, border: "none", padding: "9px 10px", cursor: "pointer" }}><Grid size={15} /></button>
            <button onClick={() => setView("list")} style={{ background: view === "list" ? T.navy : "#fff", color: view === "list" ? "#fff" : T.navy, border: "none", padding: "9px 10px", cursor: "pointer" }}><List size={15} /></button>
          </div>
        </div>
      </div>

      <div style={{ display: "grid", gridTemplateColumns: showFilters ? "250px 1fr" : "1fr", gap: 24 }}>
        {showFilters && (
          <aside style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 18, height: "fit-content", position: "sticky", top: 96 }}>
            <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 12 }}>Category</div>
            {["all", ...CATEGORIES.map(c => c.id)].map(cid => (
              <label key={cid} style={{ display: "flex", alignItems: "center", gap: 8, fontSize: 13.5, marginBottom: 8, cursor: "pointer", color: filters.category === cid ? T.teal : T.ink, fontWeight: filters.category === cid ? 700 : 400 }}>
                <input type="radio" checked={filters.category === cid} onChange={() => setFilters(f => ({ ...f, category: cid }))} />
                {cid === "all" ? "All Categories" : CATEGORIES.find(c => c.id === cid)?.name}
              </label>
            ))}
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "14px 0" }} />
            <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 10 }}>Price up to ₹{filters.maxPrice.toLocaleString("en-IN")}</div>
            <input type="range" min={500} max={70000} step={500} value={filters.maxPrice} onChange={e => setFilters(f => ({ ...f, maxPrice: Number(e.target.value) }))} style={{ width: "100%" }} />
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "14px 0" }} />
            <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 10 }}>Brand</div>
            {BRANDS.map(b => (
              <label key={b} style={{ display: "flex", alignItems: "center", gap: 8, fontSize: 13.5, marginBottom: 8, cursor: "pointer" }}>
                <input type="checkbox" checked={filters.brands.includes(b)} onChange={() => toggleBrand(b)} /> {b}
              </label>
            ))}
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "14px 0" }} />
            <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 10 }}>Minimum Rating</div>
            {[4.5, 4, 3, 0].map(r => (
              <label key={r} style={{ display: "flex", alignItems: "center", gap: 8, fontSize: 13.5, marginBottom: 8, cursor: "pointer" }}>
                <input type="radio" checked={filters.minRating === r} onChange={() => setFilters(f => ({ ...f, minRating: r }))} />
                {r === 0 ? "Any rating" : <span style={{ display: "flex", alignItems: "center", gap: 5 }}><Stars rating={r} size={12} /> &amp; up</span>}
              </label>
            ))}
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "14px 0" }} />
            <div style={{ fontWeight: 700, fontSize: 14, marginBottom: 10 }}>Discount</div>
            {[50, 30, 10, 0].map(d => (
              <label key={d} style={{ display: "flex", alignItems: "center", gap: 8, fontSize: 13.5, marginBottom: 8, cursor: "pointer" }}>
                <input type="radio" checked={filters.minDiscount === d} onChange={() => setFilters(f => ({ ...f, minDiscount: d }))} />
                {d === 0 ? "Any discount" : `${d}% or more`}
              </label>
            ))}
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "14px 0" }} />
            <label style={{ display: "flex", alignItems: "center", gap: 8, fontSize: 13.5, cursor: "pointer", fontWeight: 600, marginBottom: 8 }}>
              <input type="checkbox" checked={filters.inStockOnly} onChange={e => setFilters(f => ({ ...f, inStockOnly: e.target.checked }))} /> In stock only
            </label>
            <Btn size="sm" variant="ghost" full onClick={() => setFilters({ category: "all", brands: [], maxPrice: 70000, minRating: 0, minDiscount: 0, inStockOnly: false })}>Clear all filters</Btn>
          </aside>
        )}

        <div>
          {filtered.length === 0 ? (
            <div style={{ textAlign: "center", padding: "80px 0", color: T.sub }}>No products match these filters. Try adjusting them.</div>
          ) : (
            <div style={{ display: "grid", gridTemplateColumns: view === "grid" ? "repeat(auto-fill,minmax(220px,1fr))" : "1fr", gap: 16 }}>
              {filtered.map(p => (
                view === "grid"
                  ? <ProductCard key={p.id} p={p} {...cartActions} onOpen={(pp) => nav("product", { id: pp.id })} wished={wishlist.includes(p.id)} />
                  : (
                    <div key={p.id} style={{ display: "flex", gap: 16, background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 14, cursor: "pointer" }} onClick={() => nav("product", { id: p.id })}>
                      <img src={p.img} style={{ width: 140, height: 140, objectFit: "cover", borderRadius: 12 }} />
                      <div style={{ flex: 1 }}>
                        <div style={{ fontSize: 12, color: T.sub, fontWeight: 600 }}>{p.brand}</div>
                        <div style={{ fontWeight: 700, fontSize: 16, margin: "3px 0" }}>{p.name}</div>
                        <Stars rating={p.rating} size={13} />
                        <div style={{ margin: "8px 0" }}><Price price={p.price} mrp={p.mrp} size="lg" /></div>
                        <div style={{ display: "flex", gap: 8 }} onClick={e => e.stopPropagation()}>
                          <Btn size="sm" variant="ghost" onClick={() => cartActions.onAddCart(p)}>Add to Cart</Btn>
                          <Btn size="sm" variant="accent" onClick={() => cartActions.onBuyNow(p)}>Buy Now</Btn>
                        </div>
                      </div>
                    </div>
                  )
              ))}
            </div>
          )}
        </div>
      </div>
    </div>
  );
}

/* ============================================================
   PRODUCT DETAIL PAGE
============================================================ */
function ProductDetailPage({ id, nav, cartActions, wishlist }) {
  const p = PRODUCTS.find(x => x.id === id) || PRODUCTS[0];
  const [imgIdx, setImgIdx] = useState(0);
  const [zoom, setZoom] = useState(false);
  const [qty, setQty] = useState(1);
  const [size, setSize] = useState(p.sizes ? p.sizes[1] : null);
  const [color, setColor] = useState(p.colors[0]);
  const images = [p.img, p.img2, p.img];
  const reviews = useMemo(() => makeReviews(p.id.length), [p.id]);
  const related = PRODUCTS.filter(x => x.cat === p.cat && x.id !== p.id).slice(0, 4);

  useEffect(() => { setImgIdx(0); setQty(1); setSize(p.sizes ? p.sizes[1] : null); setColor(p.colors[0]); window.scrollTo(0, 0); }, [id]);

  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "24px 20px 60px" }}>
      <div style={{ fontSize: 13, color: T.sub, marginBottom: 16, display: "flex", alignItems: "center", gap: 6, flexWrap: "wrap" }}>
        <span onClick={() => nav("home")} style={{ cursor: "pointer" }}>Home</span><ChevronRight size={13} />
        <span onClick={() => nav("listing", { category: p.cat })} style={{ cursor: "pointer" }}>{CATEGORIES.find(c => c.id === p.cat)?.name}</span><ChevronRight size={13} />
        <span style={{ color: T.ink, fontWeight: 600 }}>{p.name}</span>
      </div>

      <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 44 }} className="pdp-grid">
        <div>
          <div style={{ display: "flex", gap: 12 }}>
            <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
              {images.map((im, i) => (
                <img key={i} src={im} onClick={() => setImgIdx(i)} style={{ width: 62, height: 62, objectFit: "cover", borderRadius: 10, cursor: "pointer", border: imgIdx === i ? `2px solid ${T.teal}` : `2px solid ${T.line}` }} />
              ))}
            </div>
            <div
              onMouseEnter={() => setZoom(true)} onMouseLeave={() => setZoom(false)}
              style={{ flex: 1, aspectRatio: "1/1", borderRadius: 18, overflow: "hidden", background: "#F0F1F6", position: "relative", cursor: "zoom-in" }}
            >
              <img src={images[imgIdx]} style={{ width: "100%", height: "100%", objectFit: "cover", transition: "transform .3s", transform: zoom ? "scale(1.5)" : "scale(1)" }} />
              <div style={{ position: "absolute", bottom: 10, right: 10, background: "rgba(255,255,255,.9)", borderRadius: 8, padding: 6, display: "flex", alignItems: "center", gap: 4, fontSize: 11, fontWeight: 600 }}>
                <ZoomIn size={13} /> Hover to zoom
              </div>
            </div>
          </div>
        </div>

        <div>
          <div style={{ display: "flex", gap: 8, marginBottom: 10 }}>
            <Badge tone="navy">{p.brand}</Badge>
            {p.tag && <Badge tone={p.tag === "Deal" ? "coral" : "teal"}>{p.tag}</Badge>}
          </div>
          <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 26, margin: "0 0 10px", lineHeight: 1.25 }}>{p.name}</h1>
          <div style={{ display: "flex", alignItems: "center", gap: 10, marginBottom: 16 }}>
            <Stars rating={p.rating} size={16} />
            <span style={{ fontSize: 13.5, color: T.sub }}>{p.rating} rating · {p.reviews.toLocaleString("en-IN")} reviews</span>
          </div>
          <div style={{ padding: "16px 0", borderTop: `1px solid ${T.line}`, borderBottom: `1px solid ${T.line}`, marginBottom: 18 }}>
            <Price price={p.price} mrp={p.mrp} size="lg" />
            <div style={{ fontSize: 12.5, color: T.sub, marginTop: 4 }}>Inclusive of all taxes · EMI available from ₹{Math.round(p.price / 6).toLocaleString("en-IN")}/mo</div>
          </div>

          {p.sizes && (
            <div style={{ marginBottom: 18 }}>
              <div style={{ fontWeight: 700, fontSize: 13.5, marginBottom: 8 }}>Size: <span style={{ fontWeight: 400, color: T.sub }}>{size}</span></div>
              <div style={{ display: "flex", gap: 8, flexWrap: "wrap" }}>
                {p.sizes.map(s => (
                  <button key={s} onClick={() => setSize(s)} style={{ padding: "8px 14px", borderRadius: 9, border: `1.5px solid ${size === s ? T.navy : T.line}`, background: size === s ? T.navy : "#fff", color: size === s ? "#fff" : T.ink, fontWeight: 600, fontSize: 13, cursor: "pointer" }}>{s}</button>
                ))}
              </div>
            </div>
          )}

          <div style={{ marginBottom: 20 }}>
            <div style={{ fontWeight: 700, fontSize: 13.5, marginBottom: 8 }}>Color</div>
            <div style={{ display: "flex", gap: 10 }}>
              {p.colors.map(c => (
                <button key={c} onClick={() => setColor(c)} style={{ width: 30, height: 30, borderRadius: "50%", background: c, border: color === c ? `3px solid ${T.teal}` : `2px solid ${T.line}`, cursor: "pointer" }} />
              ))}
            </div>
          </div>

          <div style={{ display: "flex", alignItems: "center", gap: 16, marginBottom: 22 }}>
            <div style={{ fontWeight: 700, fontSize: 13.5 }}>Quantity</div>
            <div style={{ display: "flex", alignItems: "center", border: `1.5px solid ${T.line}`, borderRadius: 10 }}>
              <button onClick={() => setQty(q => Math.max(1, q - 1))} style={{ padding: 9, background: "none", border: "none", cursor: "pointer" }}><Minus size={15} /></button>
              <span style={{ padding: "0 16px", fontWeight: 700 }}>{qty}</span>
              <button onClick={() => setQty(q => Math.min(p.stock, q + 1))} style={{ padding: 9, background: "none", border: "none", cursor: "pointer" }}><Plus size={15} /></button>
            </div>
            <span style={{ fontSize: 12.5, color: T.sub }}>{p.stock} in stock</span>
          </div>

          <div style={{ display: "flex", gap: 12, marginBottom: 24 }}>
            <Btn variant="ghost" size="lg" full onClick={() => cartActions.onAddCart(p, qty, { size, color })}>Add to Cart</Btn>
            <Btn variant="accent" size="lg" full onClick={() => cartActions.onBuyNow(p, qty, { size, color })}>Buy Now</Btn>
            <button onClick={() => cartActions.onToggleWish(p.id)} style={{ border: `1.5px solid ${T.line}`, borderRadius: 11, width: 52, background: "#fff", cursor: "pointer" }}>
              <Heart size={19} style={{ margin: "auto" }} fill={wishlist.includes(p.id) ? T.coral : "none"} color={wishlist.includes(p.id) ? T.coral : T.navy} />
            </button>
          </div>

          <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr 1fr", gap: 10 }}>
            {[[Truck, "Free delivery", "2-4 business days"], [RotateCcw, "7-day returns", "No questions asked"], [ShieldCheck, "1-year warranty", "SmartPik Assurance"]].map(([Ic, t1, t2], i) => (
              <div key={i} style={{ background: T.bg, borderRadius: 12, padding: 12, textAlign: "center" }}>
                <Ic size={18} color={T.teal} style={{ marginBottom: 6 }} />
                <div style={{ fontSize: 12, fontWeight: 700 }}>{t1}</div>
                <div style={{ fontSize: 10.5, color: T.sub }}>{t2}</div>
              </div>
            ))}
          </div>
        </div>
      </div>

      <div style={{ marginTop: 50, display: "grid", gridTemplateColumns: "2fr 1fr", gap: 40 }} className="pdp-lower">
        <div>
          <h3 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 12 }}>Product Description</h3>
          <p style={{ color: T.sub, lineHeight: 1.75, fontSize: 14.5 }}>{p.desc}</p>

          <h3 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, margin: "28px 0 12px" }}>Specifications</h3>
          <div style={{ border: `1px solid ${T.line}`, borderRadius: 14, overflow: "hidden" }}>
            {p.specs.map(([k, v], i) => (
              <div key={k} style={{ display: "flex", padding: "11px 16px", background: i % 2 ? "#fff" : T.bg, fontSize: 13.5 }}>
                <div style={{ width: 160, color: T.sub, fontWeight: 600 }}>{k}</div><div>{v}</div>
              </div>
            ))}
          </div>

          <h3 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, margin: "28px 0 12px" }}>Customer Reviews</h3>
          <div style={{ display: "flex", gap: 20, marginBottom: 18, alignItems: "center" }}>
            <div style={{ textAlign: "center" }}>
              <div style={{ fontSize: 38, fontWeight: 700, fontFamily: "'Space Grotesk',sans-serif" }}>{p.rating}</div>
              <Stars rating={p.rating} size={14} />
              <div style={{ fontSize: 12, color: T.sub, marginTop: 2 }}>{p.reviews.toLocaleString("en-IN")} reviews</div>
            </div>
            <div style={{ flex: 1 }}>
              {[5, 4, 3, 2, 1].map(star => (
                <div key={star} style={{ display: "flex", alignItems: "center", gap: 8, marginBottom: 4 }}>
                  <span style={{ fontSize: 11.5, width: 10 }}>{star}</span>
                  <div style={{ flex: 1, height: 6, background: T.line, borderRadius: 4, overflow: "hidden" }}>
                    <div style={{ width: `${star === 5 ? 62 : star === 4 ? 24 : star === 3 ? 8 : star === 2 ? 4 : 2}%`, height: "100%", background: T.gold }} />
                  </div>
                </div>
              ))}
            </div>
          </div>
          {reviews.map((r, i) => (
            <div key={i} style={{ borderTop: `1px solid ${T.line}`, padding: "16px 0" }}>
              <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 6 }}>
                <div style={{ display: "flex", alignItems: "center", gap: 8 }}>
                  <div style={{ width: 30, height: 30, borderRadius: "50%", background: T.navySoft, color: "#fff", display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 700, fontSize: 12 }}>{r.name[0]}</div>
                  <div>
                    <div style={{ fontWeight: 700, fontSize: 13.5 }}>{r.name} {r.verified && <span style={{ color: T.teal, fontSize: 11, fontWeight: 600 }}>✓ Verified</span>}</div>
                    <Stars rating={r.rating} size={12} />
                  </div>
                </div>
                <span style={{ fontSize: 12, color: T.sub }}>{r.date}</span>
              </div>
              <p style={{ fontSize: 13.5, color: T.ink, lineHeight: 1.6, margin: 0 }}>{r.text}</p>
            </div>
          ))}
        </div>

        <div>
          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 18 }}>
            <div style={{ fontWeight: 700, marginBottom: 12, display: "flex", alignItems: "center", gap: 8 }}><Truck size={17} color={T.teal} /> Delivery Information</div>
            <div style={{ fontSize: 13, color: T.sub, lineHeight: 1.7 }}>Enter your pincode to check delivery time.</div>
            <div style={{ display: "flex", gap: 8, marginTop: 10 }}>
              <input placeholder="Pincode" style={{ flex: 1, padding: "9px 12px", borderRadius: 9, border: `1px solid ${T.line}` }} />
              <Btn size="sm" variant="ghost">Check</Btn>
            </div>
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "16px 0" }} />
            <div style={{ fontWeight: 700, marginBottom: 8, display: "flex", alignItems: "center", gap: 8 }}><RotateCcw size={17} color={T.teal} /> Returns &amp; Refunds</div>
            <p style={{ fontSize: 13, color: T.sub, lineHeight: 1.7 }}>Free 7-day returns. Refunds are processed to your original payment method within 3-5 business days of pickup.</p>
          </div>
        </div>
      </div>

      {related.length > 0 && (
        <div style={{ marginTop: 50 }}>
          <SectionHead eyebrow="You may also like" title="Related Products" />
          <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill,minmax(220px,1fr))", gap: 16 }}>
            {related.map(rp => <ProductCard key={rp.id} p={rp} {...cartActions} onOpen={(pp) => nav("product", { id: pp.id })} wished={wishlist.includes(rp.id)} />)}
          </div>
        </div>
      )}
    </div>
  );
}

/* ============================================================
   CART PAGE
============================================================ */
function CartPage({ cart, setCart, nav, wishlist, toggleWish }) {
  const [coupon, setCoupon] = useState("");
  const [applied, setApplied] = useState(null);

  const lines = cart.map(item => ({ ...item, p: PRODUCTS.find(p => p.id === item.id) }));
  const subtotal = lines.reduce((s, l) => s + l.p.price * l.qty, 0);
  const mrpTotal = lines.reduce((s, l) => s + l.p.mrp * l.qty, 0);
  const discount = mrpTotal - subtotal;
  const couponDiscount = applied ? Math.round(subtotal * applied.pct) : 0;
  const delivery = subtotal > 499 || subtotal === 0 ? 0 : 79;
  const total = subtotal - couponDiscount + delivery;

  const setQty = (idx, q) => setCart(c => c.map((it, i) => i === idx ? { ...it, qty: Math.max(1, q) } : it));
  const removeItem = (idx) => setCart(c => c.filter((_, i) => i !== idx));

  const applyCoupon = () => {
    const code = coupon.trim().toUpperCase();
    if (code === "SMART10") setApplied({ code, pct: 0.10 });
    else if (code === "WELCOME50") setApplied({ code, pct: 0.05 });
    else setApplied(null);
  };

  return (
    <div style={{ maxWidth: 1100, margin: "0 auto", padding: "28px 20px 60px" }}>
      <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 26, marginBottom: 20 }}>Shopping Cart</h1>
      {lines.length === 0 ? (
        <div style={{ textAlign: "center", padding: "70px 0" }}>
          <ShoppingCart size={44} color={T.line} style={{ marginBottom: 14 }} />
          <div style={{ fontSize: 16, fontWeight: 700, marginBottom: 6 }}>Your cart is empty</div>
          <div style={{ color: T.sub, marginBottom: 18, fontSize: 14 }}>Looks like you haven't added anything yet.</div>
          <Btn variant="accent" onClick={() => nav("listing", {})}>Start Shopping</Btn>
        </div>
      ) : (
        <div style={{ display: "grid", gridTemplateColumns: "1fr 340px", gap: 28 }} className="cart-grid">
          <div style={{ display: "flex", flexDirection: "column", gap: 12 }}>
            {lines.map((l, idx) => (
              <div key={idx} style={{ display: "flex", gap: 14, background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 14 }}>
                <img src={l.p.img} style={{ width: 96, height: 96, objectFit: "cover", borderRadius: 12, cursor: "pointer" }} onClick={() => nav("product", { id: l.p.id })} />
                <div style={{ flex: 1 }}>
                  <div style={{ display: "flex", justifyContent: "space-between", gap: 10 }}>
                    <div>
                      <div style={{ fontSize: 12, color: T.sub, fontWeight: 600 }}>{l.p.brand}</div>
                      <div style={{ fontWeight: 700, fontSize: 14.5, cursor: "pointer" }} onClick={() => nav("product", { id: l.p.id })}>{l.p.name}</div>
                      {(l.variant?.size || l.variant?.color) && (
                        <div style={{ fontSize: 12, color: T.sub, marginTop: 3 }}>
                          {l.variant?.size && <>Size: {l.variant.size} &nbsp;</>}
                          {l.variant?.color && <>Color: <span style={{ display: "inline-block", width: 10, height: 10, borderRadius: "50%", background: l.variant.color, verticalAlign: "middle" }} /></>}
                        </div>
                      )}
                    </div>
                    <Price price={l.p.price} mrp={l.p.mrp} size="sm" />
                  </div>
                  <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginTop: 12 }}>
                    <div style={{ display: "flex", alignItems: "center", border: `1.5px solid ${T.line}`, borderRadius: 9 }}>
                      <button onClick={() => setQty(idx, l.qty - 1)} style={{ padding: 6, background: "none", border: "none", cursor: "pointer" }}><Minus size={13} /></button>
                      <span style={{ padding: "0 12px", fontWeight: 700, fontSize: 13 }}>{l.qty}</span>
                      <button onClick={() => setQty(idx, l.qty + 1)} style={{ padding: 6, background: "none", border: "none", cursor: "pointer" }}><Plus size={13} /></button>
                    </div>
                    <div style={{ display: "flex", gap: 14 }}>
                      <button onClick={() => { toggleWish(l.p.id); }} style={{ background: "none", border: "none", cursor: "pointer", color: T.sub, fontSize: 12.5, display: "flex", gap: 4, alignItems: "center" }}>
                        <Heart size={14} fill={wishlist.includes(l.p.id) ? T.coral : "none"} color={wishlist.includes(l.p.id) ? T.coral : T.sub} /> Wishlist
                      </button>
                      <button onClick={() => removeItem(idx)} style={{ background: "none", border: "none", cursor: "pointer", color: T.coral, fontSize: 12.5, display: "flex", gap: 4, alignItems: "center" }}>
                        <Trash2 size={14} /> Remove
                      </button>
                    </div>
                  </div>
                </div>
              </div>
            ))}
          </div>

          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 20, height: "fit-content", position: "sticky", top: 96 }}>
            <div style={{ fontWeight: 700, marginBottom: 14 }}>Order Summary</div>
            <div style={{ display: "flex", gap: 8, marginBottom: 14 }}>
              <input value={coupon} onChange={e => setCoupon(e.target.value)} placeholder="Coupon code (try SMART10)" style={{ flex: 1, padding: "9px 12px", borderRadius: 9, border: `1px solid ${T.line}`, fontSize: 13 }} />
              <Btn size="sm" variant="ghost" icon={Tag} onClick={applyCoupon}>Apply</Btn>
            </div>
            {applied && <div style={{ fontSize: 12.5, color: T.teal, marginBottom: 10, fontWeight: 600 }}>Coupon "{applied.code}" applied ✓</div>}
            {[["Subtotal (MRP)", `₹${mrpTotal.toLocaleString("en-IN")}`], ["Product discount", `-₹${discount.toLocaleString("en-IN")}`], ["Coupon discount", `-₹${couponDiscount.toLocaleString("en-IN")}`], ["Delivery", delivery === 0 ? "FREE" : `₹${delivery}`]].map(([k, v]) => (
              <div key={k} style={{ display: "flex", justifyContent: "space-between", fontSize: 13.5, color: T.sub, marginBottom: 9 }}><span>{k}</span><span style={{ color: T.ink, fontWeight: 600 }}>{v}</span></div>
            ))}
            <hr style={{ border: "none", borderTop: `1px solid ${T.line}`, margin: "12px 0" }} />
            <div style={{ display: "flex", justifyContent: "space-between", fontSize: 17, fontWeight: 700, marginBottom: 18 }}><span>Total</span><span>₹{total.toLocaleString("en-IN")}</span></div>
            <Btn variant="accent" full size="lg" onClick={() => nav("checkout")}>Proceed to Checkout</Btn>
          </div>
        </div>
      )}
    </div>
  );
}

/* ============================================================
   WISHLIST PAGE
============================================================ */
function WishlistPage({ wishlist, nav, cartActions }) {
  const items = PRODUCTS.filter(p => wishlist.includes(p.id));
  return (
    <div style={{ maxWidth: 1280, margin: "0 auto", padding: "28px 20px 60px" }}>
      <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 26, marginBottom: 20 }}>My Wishlist ({items.length})</h1>
      {items.length === 0 ? (
        <div style={{ textAlign: "center", padding: "70px 0" }}>
          <Heart size={44} color={T.line} style={{ marginBottom: 14 }} />
          <div style={{ fontSize: 16, fontWeight: 700, marginBottom: 6 }}>Your wishlist is empty</div>
          <Btn variant="accent" onClick={() => nav("listing", {})}>Browse Products</Btn>
        </div>
      ) : (
        <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill,minmax(220px,1fr))", gap: 16 }}>
          {items.map(p => <ProductCard key={p.id} p={p} {...cartActions} onOpen={(pp) => nav("product", { id: pp.id })} wished={true} />)}
        </div>
      )}
    </div>
  );
}

/* ============================================================
   CHECKOUT PAGE
============================================================ */
function CheckoutPage({ cart, nav, clearCart }) {
  const [step, setStep] = useState(1);
  const [guest, setGuest] = useState(null);
  const [address, setAddress] = useState({ name: "", phone: "", line1: "", city: "", state: "", pincode: "" });
  const [payment, setPayment] = useState("upi");
  const [orderId] = useState(() => "SPK" + Math.floor(100000 + Math.random() * 900000));

  const lines = cart.map(item => ({ ...item, p: PRODUCTS.find(p => p.id === item.id) }));
  const subtotal = lines.reduce((s, l) => s + l.p.price * l.qty, 0);
  const delivery = subtotal > 499 || subtotal === 0 ? 0 : 79;
  const total = subtotal + delivery;

  const steps = ["Login", "Address", "Order Summary", "Payment", "Confirmation"];

  const addrValid = address.name && address.phone && address.line1 && address.city && address.pincode;

  return (
    <div style={{ maxWidth: 900, margin: "0 auto", padding: "28px 20px 70px" }}>
      <div style={{ display: "flex", justifyContent: "center", marginBottom: 34, flexWrap: "wrap", gap: 4 }}>
        {steps.map((s, i) => (
          <div key={s} style={{ display: "flex", alignItems: "center" }}>
            <div style={{ display: "flex", flexDirection: "column", alignItems: "center", gap: 6 }}>
              <div style={{
                width: 32, height: 32, borderRadius: "50%", display: "flex", alignItems: "center", justifyContent: "center",
                background: step > i + 1 ? T.teal : step === i + 1 ? T.navy : "#fff", color: step >= i + 1 ? "#fff" : T.sub,
                border: `2px solid ${step >= i + 1 ? (step > i + 1 ? T.teal : T.navy) : T.line}`, fontWeight: 700, fontSize: 13,
              }}>{step > i + 1 ? <Check size={15} /> : i + 1}</div>
              <span style={{ fontSize: 11, color: step === i + 1 ? T.ink : T.sub, fontWeight: step === i + 1 ? 700 : 400 }}>{s}</span>
            </div>
            {i < steps.length - 1 && <div style={{ width: 40, height: 2, background: step > i + 1 ? T.teal : T.line, margin: "0 4px 18px" }} />}
          </div>
        ))}
      </div>

      <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 18, padding: 28 }}>
        {step === 1 && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 21, marginBottom: 18 }}>Login or Continue as Guest</h2>
            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 16 }} className="checkout-2col">
              <div style={{ border: `1.5px solid ${T.line}`, borderRadius: 14, padding: 18 }}>
                <div style={{ fontWeight: 700, marginBottom: 10 }}>Login to your account</div>
                <input placeholder="Email or phone number" style={{ width: "100%", padding: "10px 12px", borderRadius: 9, border: `1px solid ${T.line}`, marginBottom: 10 }} />
                <input placeholder="Password" type="password" style={{ width: "100%", padding: "10px 12px", borderRadius: 9, border: `1px solid ${T.line}`, marginBottom: 14 }} />
                <Btn variant="primary" full onClick={() => { setGuest(false); setStep(2); }}>Login &amp; Continue</Btn>
              </div>
              <div style={{ border: `1.5px solid ${T.line}`, borderRadius: 14, padding: 18, display: "flex", flexDirection: "column", justifyContent: "center", alignItems: "center", textAlign: "center", gap: 10 }}>
                <div style={{ fontWeight: 700 }}>Checkout as Guest</div>
                <p style={{ fontSize: 13, color: T.sub }}>Quick checkout without creating an account.</p>
                <Btn variant="outline" full onClick={() => { setGuest(true); setStep(2); }}>Continue as Guest</Btn>
              </div>
            </div>
          </div>
        )}

        {step === 2 && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 21, marginBottom: 18 }}>Delivery Address</h2>
            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 12 }} className="checkout-2col">
              <input placeholder="Full name" value={address.name} onChange={e => setAddress(a => ({ ...a, name: e.target.value }))} style={inp} />
              <input placeholder="Phone number" value={address.phone} onChange={e => setAddress(a => ({ ...a, phone: e.target.value }))} style={inp} />
              <input placeholder="Address line" value={address.line1} onChange={e => setAddress(a => ({ ...a, line1: e.target.value }))} style={{ ...inp, gridColumn: "1/3" }} />
              <input placeholder="City" value={address.city} onChange={e => setAddress(a => ({ ...a, city: e.target.value }))} style={inp} />
              <input placeholder="State" value={address.state} onChange={e => setAddress(a => ({ ...a, state: e.target.value }))} style={inp} />
              <input placeholder="Pincode" value={address.pincode} onChange={e => setAddress(a => ({ ...a, pincode: e.target.value }))} style={inp} />
              <select style={inp}><option>Home</option><option>Work</option><option>Other</option></select>
            </div>
            <div style={{ display: "flex", justifyContent: "space-between", marginTop: 22 }}>
              <Btn variant="ghost" icon={ArrowLeft} onClick={() => setStep(1)}>Back</Btn>
              <Btn variant="accent" disabled={!addrValid} onClick={() => setStep(3)}>Continue to Order Summary</Btn>
            </div>
          </div>
        )}

        {step === 3 && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 21, marginBottom: 18 }}>Order Summary</h2>
            <div style={{ display: "flex", flexDirection: "column", gap: 10, marginBottom: 18 }}>
              {lines.map((l, i) => (
                <div key={i} style={{ display: "flex", gap: 12, alignItems: "center" }}>
                  <img src={l.p.img} style={{ width: 52, height: 52, borderRadius: 9, objectFit: "cover" }} />
                  <div style={{ flex: 1 }}>
                    <div style={{ fontWeight: 600, fontSize: 13.5 }}>{l.p.name}</div>
                    <div style={{ fontSize: 12, color: T.sub }}>Qty: {l.qty}</div>
                  </div>
                  <div style={{ fontWeight: 700, fontSize: 13.5 }}>₹{(l.p.price * l.qty).toLocaleString("en-IN")}</div>
                </div>
              ))}
            </div>
            <div style={{ background: T.bg, borderRadius: 12, padding: 14, fontSize: 13.5, marginBottom: 18 }}>
              <div style={{ fontWeight: 700, marginBottom: 6 }}>Deliver to</div>
              <div style={{ color: T.sub }}>{address.name}, {address.line1}, {address.city}, {address.state} - {address.pincode} · {address.phone}</div>
            </div>
            <div style={{ display: "flex", justifyContent: "space-between", fontSize: 13.5, marginBottom: 6 }}><span>Subtotal</span><span>₹{subtotal.toLocaleString("en-IN")}</span></div>
            <div style={{ display: "flex", justifyContent: "space-between", fontSize: 13.5, marginBottom: 10 }}><span>Delivery</span><span>{delivery === 0 ? "FREE" : `₹${delivery}`}</span></div>
            <div style={{ display: "flex", justifyContent: "space-between", fontWeight: 700, fontSize: 16, borderTop: `1px solid ${T.line}`, paddingTop: 10 }}><span>Total</span><span>₹{total.toLocaleString("en-IN")}</span></div>
            <div style={{ display: "flex", justifyContent: "space-between", marginTop: 22 }}>
              <Btn variant="ghost" icon={ArrowLeft} onClick={() => setStep(2)}>Back</Btn>
              <Btn variant="accent" onClick={() => setStep(4)}>Continue to Payment</Btn>
            </div>
          </div>
        )}

        {step === 4 && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 21, marginBottom: 18 }}>Payment Method</h2>
            <div style={{ display: "flex", flexDirection: "column", gap: 10, marginBottom: 20 }}>
              {[
                { id: "upi", label: "UPI", sub: "Pay via Google Pay, PhonePe, Paytm", icon: Smartphone },
                { id: "card", label: "Credit / Debit Card", sub: "Visa, Mastercard, RuPay accepted", icon: CreditCard },
                { id: "netbanking", label: "Net Banking", sub: "All major Indian banks", icon: Building2 },
                { id: "cod", label: "Cash on Delivery", sub: "Pay when your order arrives", icon: Banknote },
              ].map(opt => (
                <label key={opt.id} style={{ display: "flex", alignItems: "center", gap: 14, border: `1.5px solid ${payment === opt.id ? T.teal : T.line}`, borderRadius: 12, padding: 14, cursor: "pointer", background: payment === opt.id ? "#F0FBF9" : "#fff" }}>
                  <input type="radio" checked={payment === opt.id} onChange={() => setPayment(opt.id)} />
                  <opt.icon size={20} color={T.navy} />
                  <div><div style={{ fontWeight: 700, fontSize: 14 }}>{opt.label}</div><div style={{ fontSize: 12, color: T.sub }}>{opt.sub}</div></div>
                </label>
              ))}
            </div>
            {payment === "card" && (
              <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 10, marginBottom: 16 }} className="checkout-2col">
                <input placeholder="Card number" style={{ ...inp, gridColumn: "1/3" }} />
                <input placeholder="MM/YY" style={inp} />
                <input placeholder="CVV" style={inp} />
              </div>
            )}
            {payment === "upi" && <input placeholder="yourname@upi" style={{ ...inp, width: "100%", marginBottom: 16 }} />}
            <div style={{ display: "flex", justifyContent: "space-between", fontWeight: 700, fontSize: 16, marginBottom: 18 }}><span>Amount payable</span><span>₹{total.toLocaleString("en-IN")}</span></div>
            <div style={{ display: "flex", justifyContent: "space-between" }}>
              <Btn variant="ghost" icon={ArrowLeft} onClick={() => setStep(3)}>Back</Btn>
              <Btn variant="coral" size="lg" onClick={() => { setStep(5); clearCart(); }}>Place Order · ₹{total.toLocaleString("en-IN")}</Btn>
            </div>
          </div>
        )}

        {step === 5 && (
          <div style={{ textAlign: "center", padding: "20px 0" }}>
            <div style={{ width: 68, height: 68, borderRadius: "50%", background: "#E3FBF7", display: "flex", alignItems: "center", justifyContent: "center", margin: "0 auto 18px" }}>
              <CheckCircle2 size={36} color={T.teal} />
            </div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 24, marginBottom: 8 }}>Order Confirmed!</h2>
            <p style={{ color: T.sub, marginBottom: 4 }}>Your order <strong style={{ color: T.ink }}>#{orderId}</strong> has been placed successfully.</p>
            <p style={{ color: T.sub, marginBottom: 24, fontSize: 13.5 }}>A confirmation has been sent to your email. Estimated delivery: 3-5 business days.</p>
            <div style={{ display: "flex", gap: 12, justifyContent: "center" }}>
              <Btn variant="outline" onClick={() => nav("account", { tab: "orders" })}>Track Order</Btn>
              <Btn variant="accent" onClick={() => nav("home")}>Continue Shopping</Btn>
            </div>
          </div>
        )}
      </div>
    </div>
  );
}
const inp = { padding: "10px 12px", borderRadius: 9, border: `1px solid ${T.line}`, fontSize: 13.5, fontFamily: "'Inter',sans-serif" };

/* ============================================================
   ACCOUNT DASHBOARD
============================================================ */
const MOCK_ORDERS = [
  { id: "SPK482910", date: "12 Aug 2026", items: 2, total: 6798, status: "Delivered", track: 4 },
  { id: "SPK481223", date: "02 Aug 2026", items: 1, total: 8749, status: "Out for Delivery", track: 3 },
  { id: "SPK479087", date: "24 Jul 2026", items: 3, total: 4599, status: "Shipped", track: 2 },
  { id: "SPK475502", date: "10 Jul 2026", items: 1, total: 2999, status: "Processing", track: 1 },
];

function AccountPage({ params, nav, wishlist, cartActions }) {
  const [tab, setTab] = useState(params.tab || "profile");
  const tabs = [
    { id: "profile", label: "Profile", icon: User },
    { id: "orders", label: "My Orders", icon: Package },
    { id: "wishlist", label: "Wishlist", icon: Heart },
    { id: "addresses", label: "Saved Addresses", icon: MapPin },
    { id: "payments", label: "Payment Methods", icon: CreditCard },
    { id: "notifications", label: "Notifications", icon: Bell },
  ];
  const wItems = PRODUCTS.filter(p => wishlist.includes(p.id));

  return (
    <div style={{ maxWidth: 1180, margin: "0 auto", padding: "28px 20px 70px", display: "grid", gridTemplateColumns: "250px 1fr", gap: 26 }} className="account-grid">
      <aside style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 16, height: "fit-content" }}>
        <div style={{ display: "flex", alignItems: "center", gap: 10, padding: "6px 6px 16px", borderBottom: `1px solid ${T.line}`, marginBottom: 10 }}>
          <div style={{ width: 40, height: 40, borderRadius: "50%", background: T.navy, color: "#fff", display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 700 }}>A</div>
          <div><div style={{ fontWeight: 700, fontSize: 14 }}>Aarav Mehta</div><div style={{ fontSize: 11.5, color: T.sub }}>aarav.mehta@email.com</div></div>
        </div>
        {tabs.map(t => (
          <div key={t.id} onClick={() => setTab(t.id)} style={{ display: "flex", alignItems: "center", gap: 10, padding: "10px 10px", borderRadius: 10, cursor: "pointer", marginBottom: 3, background: tab === t.id ? T.bg : "transparent", color: tab === t.id ? T.teal : T.ink, fontWeight: tab === t.id ? 700 : 500, fontSize: 13.5 }}>
            <t.icon size={16} /> {t.label}
          </div>
        ))}
        <div style={{ display: "flex", alignItems: "center", gap: 10, padding: "10px 10px", borderRadius: 10, cursor: "pointer", color: T.coral, fontWeight: 600, fontSize: 13.5, marginTop: 8, borderTop: `1px solid ${T.line}`, paddingTop: 14 }} onClick={() => nav("home")}>
          <LogOut size={16} /> Logout
        </div>
      </aside>

      <div>
        {tab === "profile" && (
          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 24 }}>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 18 }}>My Profile</h2>
            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 14 }} className="checkout-2col">
              <div><div style={lbl}>Full name</div><input defaultValue="Aarav Mehta" style={inp2} /></div>
              <div><div style={lbl}>Email</div><input defaultValue="aarav.mehta@email.com" style={inp2} /></div>
              <div><div style={lbl}>Phone</div><input defaultValue="+91 98765 43210" style={inp2} /></div>
              <div><div style={lbl}>Date of birth</div><input defaultValue="14 Mar 1996" style={inp2} /></div>
            </div>
            <div style={{ marginTop: 20 }}><Btn variant="accent">Save Changes</Btn></div>
          </div>
        )}

        {tab === "orders" && (
          <div style={{ display: "flex", flexDirection: "column", gap: 14 }}>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20 }}>My Orders</h2>
            {MOCK_ORDERS.map(o => (
              <div key={o.id} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 18 }}>
                <div style={{ display: "flex", justifyContent: "space-between", flexWrap: "wrap", gap: 10, marginBottom: 14 }}>
                  <div>
                    <div style={{ fontWeight: 700, fontSize: 14.5 }}>Order #{o.id}</div>
                    <div style={{ fontSize: 12.5, color: T.sub }}>Placed on {o.date} · {o.items} item{o.items > 1 ? "s" : ""} · ₹{o.total.toLocaleString("en-IN")}</div>
                  </div>
                  <Badge tone={o.status === "Delivered" ? "teal" : "gold"}>{o.status}</Badge>
                </div>
                <div style={{ display: "flex", alignItems: "center" }}>
                  {["Placed", "Shipped", "Out for Delivery", "Delivered"].map((s, i) => (
                    <React.Fragment key={s}>
                      <div style={{ display: "flex", flexDirection: "column", alignItems: "center", gap: 4 }}>
                        <div style={{ width: 22, height: 22, borderRadius: "50%", background: o.track >= i + 1 ? T.teal : T.line, display: "flex", alignItems: "center", justifyContent: "center" }}>
                          {o.track >= i + 1 && <Check size={12} color="#fff" />}
                        </div>
                        <span style={{ fontSize: 10, color: T.sub, textAlign: "center", width: 60 }}>{s}</span>
                      </div>
                      {i < 3 && <div style={{ flex: 1, height: 2, background: o.track > i + 1 ? T.teal : T.line, marginBottom: 16 }} />}
                    </React.Fragment>
                  ))}
                </div>
              </div>
            ))}
          </div>
        )}

        {tab === "wishlist" && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 16 }}>Wishlist</h2>
            {wItems.length === 0 ? <div style={{ color: T.sub }}>No items saved yet.</div> : (
              <div style={{ display: "grid", gridTemplateColumns: "repeat(auto-fill,minmax(200px,1fr))", gap: 14 }}>
                {wItems.map(p => <ProductCard key={p.id} p={p} {...cartActions} onOpen={(pp) => nav("product", { id: pp.id })} wished={true} />)}
              </div>
            )}
          </div>
        )}

        {tab === "addresses" && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 16 }}>Saved Addresses</h2>
            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: 14 }} className="checkout-2col">
              {[{ tag: "Home", addr: "402, Silver Oak Residency, Sector 21, Bhubaneswar, Odisha - 751024" }, { tag: "Work", addr: "SmartPik Business Park, Tower B, 5th Floor, Bhubaneswar, Odisha - 751003" }].map(a => (
                <div key={a.tag} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 16 }}>
                  <Badge tone="navy">{a.tag}</Badge>
                  <p style={{ fontSize: 13.5, color: T.ink, margin: "10px 0", lineHeight: 1.6 }}>{a.addr}</p>
                  <div style={{ display: "flex", gap: 8 }}><Btn size="sm" variant="ghost" icon={Edit3}>Edit</Btn><Btn size="sm" variant="ghost" icon={Trash2}>Remove</Btn></div>
                </div>
              ))}
              <button style={{ border: `1.5px dashed ${T.line}`, borderRadius: 14, background: "none", cursor: "pointer", color: T.sub, fontWeight: 600, display: "flex", alignItems: "center", justifyContent: "center", gap: 6, minHeight: 100 }}><PlusCircle size={16} /> Add new address</button>
            </div>
          </div>
        )}

        {tab === "payments" && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 16 }}>Payment Methods</h2>
            <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
              {[{ l: "HDFC Bank Credit Card", n: "•••• •••• •••• 4821", icon: CreditCard }, { l: "UPI — Google Pay", n: "aarav.m@okhdfcbank", icon: Smartphone }].map((m, i) => (
                <div key={i} style={{ display: "flex", alignItems: "center", gap: 14, background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 16 }}>
                  <m.icon size={20} color={T.navy} />
                  <div style={{ flex: 1 }}><div style={{ fontWeight: 700, fontSize: 13.5 }}>{m.l}</div><div style={{ fontSize: 12, color: T.sub }}>{m.n}</div></div>
                  <MoreVertical size={16} color={T.sub} />
                </div>
              ))}
              <Btn variant="ghost" icon={PlusCircle}>Add Payment Method</Btn>
            </div>
          </div>
        )}

        {tab === "notifications" && (
          <div>
            <h2 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 20, marginBottom: 16 }}>Notifications</h2>
            <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
              {[
                ["Your order #SPK481223 is out for delivery", "1 hour ago"],
                ["Price drop: items in your wishlist are now on sale", "5 hours ago"],
                ["Your return for order #SPK475110 was approved", "1 day ago"],
                ["Flash sale starts tomorrow — up to 60% off electronics", "2 days ago"],
              ].map(([t, time], i) => (
                <div key={i} style={{ display: "flex", gap: 12, background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 14 }}>
                  <Bell size={17} color={T.teal} />
                  <div style={{ flex: 1 }}><div style={{ fontSize: 13.5, fontWeight: 600 }}>{t}</div><div style={{ fontSize: 11.5, color: T.sub, marginTop: 2 }}>{time}</div></div>
                </div>
              ))}
            </div>
          </div>
        )}
      </div>
    </div>
  );
}
const lbl = { fontSize: 12, fontWeight: 600, color: T.sub, marginBottom: 5 };
const inp2 = { width: "100%", padding: "10px 12px", borderRadius: 9, border: `1px solid ${T.line}`, fontSize: 13.5, boxSizing: "border-box" };

/* ============================================================
   ADMIN DASHBOARD
============================================================ */
function StatCard({ label, value, delta, icon: Icon, tone }) {
  return (
    <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 18 }}>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-start" }}>
        <div>
          <div style={{ fontSize: 12.5, color: T.sub, fontWeight: 600, marginBottom: 6 }}>{label}</div>
          <div style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 24, fontWeight: 700 }}>{value}</div>
        </div>
        <div style={{ width: 38, height: 38, borderRadius: 10, background: tone, display: "flex", alignItems: "center", justifyContent: "center" }}><Icon size={18} color="#fff" /></div>
      </div>
      <div style={{ fontSize: 12, color: T.teal, fontWeight: 700, marginTop: 10, display: "flex", alignItems: "center", gap: 4 }}><TrendingUp size={13} /> {delta} vs last month</div>
    </div>
  );
}

function AdminPage({ nav }) {
  const [tab, setTab] = useState("dashboard");
  const tabs = [
    { id: "dashboard", label: "Dashboard", icon: LayoutDashboard },
    { id: "products", label: "Products", icon: Boxes },
    { id: "categories", label: "Categories", icon: FolderTree },
    { id: "inventory", label: "Inventory", icon: Package },
    { id: "orders", label: "Orders", icon: ShoppingCart },
    { id: "customers", label: "Customers", icon: Users },
    { id: "coupons", label: "Coupons", icon: Ticket },
    { id: "banners", label: "Homepage Banners", icon: LayoutTemplate },
    { id: "reviews", label: "Reviews", icon: MessageSquare },
  ];
  const revenueData = [42, 58, 49, 71, 66, 84, 92, 77, 96, 88, 104, 118];
  const maxRev = Math.max(...revenueData);

  return (
    <div style={{ minHeight: "70vh", background: T.bg, display: "grid", gridTemplateColumns: "230px 1fr" }} className="admin-grid">
      <aside style={{ background: T.navy, padding: "20px 14px", color: "#cfd5ea" }}>
        <div onClick={() => nav("home")} style={{ display: "flex", alignItems: "center", gap: 8, cursor: "pointer", padding: "0 8px 20px" }}>
          <div style={{ width: 30, height: 30, borderRadius: 8, background: T.teal, display: "flex", alignItems: "center", justifyContent: "center" }}><Zap size={15} color="#fff" fill="#fff" /></div>
          <span style={{ fontFamily: "'Space Grotesk',sans-serif", fontWeight: 700, color: "#fff", fontSize: 16 }}>SmartPik <span style={{ opacity: .6, fontWeight: 500, fontSize: 12 }}>Admin</span></span>
        </div>
        {tabs.map(t => (
          <div key={t.id} onClick={() => setTab(t.id)} style={{ display: "flex", alignItems: "center", gap: 10, padding: "10px 12px", borderRadius: 10, cursor: "pointer", marginBottom: 2, background: tab === t.id ? "rgba(255,255,255,.08)" : "transparent", color: tab === t.id ? "#fff" : "#9BA4C4", fontWeight: tab === t.id ? 700 : 500, fontSize: 13.5 }}>
            <t.icon size={16} /> {t.label}
          </div>
        ))}
        <div onClick={() => nav("home")} style={{ display: "flex", alignItems: "center", gap: 10, padding: "10px 12px", borderRadius: 10, cursor: "pointer", color: "#9BA4C4", fontSize: 13.5, marginTop: 16, borderTop: "1px solid rgba(255,255,255,.1)", paddingTop: 16 }}>
          <ArrowLeft size={16} /> Back to Store
        </div>
      </aside>

      <div style={{ padding: "24px 28px 60px" }}>
        <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: 22 }}>
          <h1 style={{ fontFamily: "'Space Grotesk',sans-serif", fontSize: 24, margin: 0, textTransform: "capitalize" }}>{tabs.find(t => t.id === tab)?.label}</h1>
          <div style={{ display: "flex", alignItems: "center", gap: 12 }}>
            <Bell size={18} color={T.navy} />
            <div style={{ width: 34, height: 34, borderRadius: "50%", background: T.navy, color: "#fff", display: "flex", alignItems: "center", justifyContent: "center", fontWeight: 700, fontSize: 13 }}>SP</div>
          </div>
        </div>

        {tab === "dashboard" && (
          <div>
            <div style={{ display: "grid", gridTemplateColumns: "repeat(4,1fr)", gap: 16, marginBottom: 20 }} className="stat-grid">
              <StatCard label="Total Revenue" value="₹18.4L" delta="+12.6%" icon={BarChart3} tone={T.teal} />
              <StatCard label="Orders" value="2,845" delta="+8.2%" icon={ShoppingCart} tone={T.navy} />
              <StatCard label="Customers" value="9,120" delta="+4.1%" icon={Users} tone={T.coral} />
              <StatCard label="Avg. Order Value" value="₹2,145" delta="+2.4%" icon={TrendingUp} tone={"#8B5CF6"} />
            </div>
            <div style={{ display: "grid", gridTemplateColumns: "2fr 1fr", gap: 16 }} className="admin-lower">
              <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 20 }}>
                <div style={{ fontWeight: 700, marginBottom: 16 }}>Monthly Revenue (₹ thousands)</div>
                <div style={{ display: "flex", alignItems: "flex-end", gap: 8, height: 160 }}>
                  {revenueData.map((v, i) => (
                    <div key={i} style={{ flex: 1, display: "flex", flexDirection: "column", alignItems: "center", gap: 6 }}>
                      <div style={{ width: "100%", height: `${(v / maxRev) * 130}px`, background: i === revenueData.length - 1 ? T.teal : T.navySoft, borderRadius: 6 }} />
                      <span style={{ fontSize: 9.5, color: T.sub }}>{["J", "F", "M", "A", "M", "J", "J", "A", "S", "O", "N", "D"][i]}</span>
                    </div>
                  ))}
                </div>
              </div>
              <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, padding: 20 }}>
                <div style={{ fontWeight: 700, marginBottom: 14 }}>Top Categories</div>
                {[["Electronics", 34], ["Fashion", 24], ["Footwear", 18], ["Home & Kitchen", 14], ["Beauty", 10]].map(([c, v]) => (
                  <div key={c} style={{ marginBottom: 12 }}>
                    <div style={{ display: "flex", justifyContent: "space-between", fontSize: 12.5, marginBottom: 4 }}><span>{c}</span><span style={{ fontWeight: 700 }}>{v}%</span></div>
                    <div style={{ height: 6, background: T.line, borderRadius: 4 }}><div style={{ width: `${v}%`, height: "100%", background: T.teal, borderRadius: 4 }} /></div>
                  </div>
                ))}
              </div>
            </div>
          </div>
        )}

        {tab === "products" && (
          <div>
            <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 14 }}>
              <input placeholder="Search products..." style={{ ...inp2, width: 280 }} />
              <Btn variant="accent" icon={PlusCircle}>Add Product</Btn>
            </div>
            <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, overflow: "hidden" }}>
              <table style={{ width: "100%", borderCollapse: "collapse", fontSize: 13 }}>
                <thead><tr style={{ background: T.bg, textAlign: "left" }}>{["Product", "Category", "Price", "Stock", "Rating", ""].map(h => <th key={h} style={{ padding: "11px 16px", fontSize: 11.5, color: T.sub, fontWeight: 700, textTransform: "uppercase" }}>{h}</th>)}</tr></thead>
                <tbody>
                  {PRODUCTS.slice(0, 9).map(p => (
                    <tr key={p.id} style={{ borderTop: `1px solid ${T.line}` }}>
                      <td style={{ padding: "10px 16px", display: "flex", alignItems: "center", gap: 10 }}><img src={p.img} style={{ width: 34, height: 34, borderRadius: 7, objectFit: "cover" }} /><span style={{ fontWeight: 600 }}>{p.name.slice(0, 28)}{p.name.length > 28 ? "…" : ""}</span></td>
                      <td style={{ padding: "10px 16px", color: T.sub }}>{CATEGORIES.find(c => c.id === p.cat)?.name}</td>
                      <td style={{ padding: "10px 16px", fontWeight: 700 }}>₹{p.price.toLocaleString("en-IN")}</td>
                      <td style={{ padding: "10px 16px" }}><Badge tone={p.stock < 15 ? "coral" : "teal"}>{p.stock} units</Badge></td>
                      <td style={{ padding: "10px 16px" }}>⭐ {p.rating}</td>
                      <td style={{ padding: "10px 16px", display: "flex", gap: 10 }}><Edit3 size={15} color={T.sub} style={{ cursor: "pointer" }} /><Trash2 size={15} color={T.coral} style={{ cursor: "pointer" }} /></td>
                    </tr>
                  ))}
                </tbody>
              </table>
            </div>
          </div>
        )}

        {tab === "categories" && (
          <div style={{ display: "grid", gridTemplateColumns: "repeat(4,1fr)", gap: 14 }} className="stat-grid">
            {CATEGORIES.map(c => (
              <div key={c.id} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 16, display: "flex", justifyContent: "space-between", alignItems: "center" }}>
                <div><div style={{ fontSize: 22, marginBottom: 6 }}>{c.icon}</div><div style={{ fontWeight: 700, fontSize: 13.5 }}>{c.name}</div><div style={{ fontSize: 11.5, color: T.sub }}>{c.count} products</div></div>
                <Edit3 size={15} color={T.sub} style={{ cursor: "pointer" }} />
              </div>
            ))}
            <button style={{ border: `1.5px dashed ${T.line}`, borderRadius: 14, background: "none", cursor: "pointer", color: T.sub, fontWeight: 600, display: "flex", alignItems: "center", justifyContent: "center", gap: 6 }}><PlusCircle size={16} /> New category</button>
          </div>
        )}

        {tab === "inventory" && (
          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, overflow: "hidden" }}>
            <table style={{ width: "100%", borderCollapse: "collapse", fontSize: 13 }}>
              <thead><tr style={{ background: T.bg, textAlign: "left" }}>{["SKU", "Product", "In Stock", "Reserved", "Status"].map(h => <th key={h} style={{ padding: "11px 16px", fontSize: 11.5, color: T.sub, fontWeight: 700, textTransform: "uppercase" }}>{h}</th>)}</tr></thead>
              <tbody>
                {PRODUCTS.slice(0, 10).map(p => (
                  <tr key={p.id} style={{ borderTop: `1px solid ${T.line}` }}>
                    <td style={{ padding: "10px 16px", color: T.sub }}>{p.id}</td>
                    <td style={{ padding: "10px 16px", fontWeight: 600 }}>{p.name.slice(0, 30)}</td>
                    <td style={{ padding: "10px 16px" }}>{p.stock}</td>
                    <td style={{ padding: "10px 16px" }}>{Math.max(0, 20 - p.stock)}</td>
                    <td style={{ padding: "10px 16px" }}><Badge tone={p.stock < 15 ? "coral" : "teal"}>{p.stock < 15 ? "Low Stock" : "Healthy"}</Badge></td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        )}

        {tab === "orders" && (
          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, overflow: "hidden" }}>
            <table style={{ width: "100%", borderCollapse: "collapse", fontSize: 13 }}>
              <thead><tr style={{ background: T.bg, textAlign: "left" }}>{["Order ID", "Customer", "Date", "Amount", "Status"].map(h => <th key={h} style={{ padding: "11px 16px", fontSize: 11.5, color: T.sub, fontWeight: 700, textTransform: "uppercase" }}>{h}</th>)}</tr></thead>
              <tbody>
                {MOCK_ORDERS.concat([{ id: "SPK471002", date: "28 Jun 2026", items: 2, total: 5199, status: "Cancelled" }]).map((o, i) => (
                  <tr key={o.id} style={{ borderTop: `1px solid ${T.line}` }}>
                    <td style={{ padding: "10px 16px", fontWeight: 600 }}>#{o.id}</td>
                    <td style={{ padding: "10px 16px", color: T.sub }}>{["Aarav Mehta", "Diya Nair", "Kabir Chawla", "Riya Bansal", "Aarav Mehta"][i]}</td>
                    <td style={{ padding: "10px 16px", color: T.sub }}>{o.date}</td>
                    <td style={{ padding: "10px 16px", fontWeight: 700 }}>₹{o.total.toLocaleString("en-IN")}</td>
                    <td style={{ padding: "10px 16px" }}><Badge tone={o.status === "Delivered" ? "teal" : o.status === "Cancelled" ? "coral" : "gold"}>{o.status}</Badge></td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        )}

        {tab === "customers" && (
          <div style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 16, overflow: "hidden" }}>
            <table style={{ width: "100%", borderCollapse: "collapse", fontSize: 13 }}>
              <thead><tr style={{ background: T.bg, textAlign: "left" }}>{["Customer", "Email", "Orders", "Total Spent", "Joined"].map(h => <th key={h} style={{ padding: "11px 16px", fontSize: 11.5, color: T.sub, fontWeight: 700, textTransform: "uppercase" }}>{h}</th>)}</tr></thead>
              <tbody>
                {[["Aarav Mehta", "aarav.mehta@email.com", 14, 42890, "Jan 2024"], ["Diya Nair", "diya.nair@email.com", 8, 21340, "Mar 2024"], ["Kabir Chawla", "kabir.c@email.com", 22, 68120, "Nov 2023"], ["Riya Bansal", "riya.b@email.com", 5, 9980, "Jun 2025"]].map((c, i) => (
                  <tr key={i} style={{ borderTop: `1px solid ${T.line}` }}>
                    <td style={{ padding: "10px 16px", fontWeight: 600 }}>{c[0]}</td>
                    <td style={{ padding: "10px 16px", color: T.sub }}>{c[1]}</td>
                    <td style={{ padding: "10px 16px" }}>{c[2]}</td>
                    <td style={{ padding: "10px 16px", fontWeight: 700 }}>₹{c[3].toLocaleString("en-IN")}</td>
                    <td style={{ padding: "10px 16px", color: T.sub }}>{c[4]}</td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        )}

        {tab === "coupons" && (
          <div>
            <div style={{ display: "flex", justifyContent: "flex-end", marginBottom: 14 }}><Btn variant="accent" icon={PlusCircle}>New Coupon</Btn></div>
            <div style={{ display: "grid", gridTemplateColumns: "repeat(3,1fr)", gap: 14 }} className="stat-grid">
              {[["SMART10", "10% off, min ₹999", "Active"], ["WELCOME50", "5% off for new users", "Active"], ["FEST200", "₹200 off, min ₹2000", "Expired"]].map(([code, desc, status]) => (
                <div key={code} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 16 }}>
                  <div style={{ display: "flex", justifyContent: "space-between", marginBottom: 8 }}><Badge tone="navy">{code}</Badge><Badge tone={status === "Active" ? "teal" : "coral"}>{status}</Badge></div>
                  <div style={{ fontSize: 13, color: T.sub }}>{desc}</div>
                </div>
              ))}
            </div>
          </div>
        )}

        {tab === "banners" && (
          <div style={{ display: "grid", gridTemplateColumns: "repeat(2,1fr)", gap: 14 }} className="checkout-2col">
            {[["Season Sale Hero", "Homepage top banner · Active"], ["Flash Sale — Electronics", "Deals section · Active"]].map(([t, s]) => (
              <div key={t} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 16, display: "flex", gap: 14, alignItems: "center" }}>
                <div style={{ width: 70, height: 46, borderRadius: 9, background: `linear-gradient(120deg, ${T.navy}, ${T.teal})` }} />
                <div style={{ flex: 1 }}><div style={{ fontWeight: 700, fontSize: 13.5 }}>{t}</div><div style={{ fontSize: 11.5, color: T.sub }}>{s}</div></div>
                <Edit3 size={15} color={T.sub} style={{ cursor: "pointer" }} />
              </div>
            ))}
            <button style={{ border: `1.5px dashed ${T.line}`, borderRadius: 14, background: "none", cursor: "pointer", color: T.sub, fontWeight: 600, display: "flex", alignItems: "center", justifyContent: "center", gap: 6, minHeight: 76 }}><ImageIcon size={16} /> Upload new banner</button>
          </div>
        )}

        {tab === "reviews" && (
          <div style={{ display: "flex", flexDirection: "column", gap: 10 }}>
            {makeReviews(3).concat(makeReviews(7)).map((r, i) => (
              <div key={i} style={{ background: "#fff", border: `1px solid ${T.line}`, borderRadius: 14, padding: 14, display: "flex", justifyContent: "space-between", alignItems: "center", gap: 14 }}>
                <div>
                  <div style={{ display: "flex", alignItems: "center", gap: 8, marginBottom: 4 }}><span style={{ fontWeight: 700, fontSize: 13.5 }}>{r.name}</span><Stars rating={r.rating} size={12} /></div>
                  <div style={{ fontSize: 12.5, color: T.sub }}>{r.text}</div>
                </div>
                <div style={{ display: "flex", gap: 10, flexShrink: 0 }}><Check size={16} color={T.teal} style={{ cursor: "pointer" }} /><Trash2 size={16} color={T.coral} style={{ cursor: "pointer" }} /></div>
              </div>
            ))}
          </div>
        )}
      </div>
    </div>
  );
}

/* ============================================================
   ROOT APP
============================================================ */
export default function App() {
  const [page, setPage] = useState("home");
  const [params, setParams] = useState({});
  const [cart, setCart] = useState([]);
  const [wishlist, setWishlist] = useState([]);
  const [searchQ, setSearchQ] = useState("");
  const [toast, setToast] = useState(null);

  const nav = (p, prm = {}) => { setPage(p); setParams(prm); window.scrollTo({ top: 0, behavior: "smooth" }); };

  const showToast = (msg) => { setToast(msg); setTimeout(() => setToast(null), 1800); };

  const addToCart = (p, qty = 1, variant = {}) => {
    setCart(c => {
      const idx = c.findIndex(it => it.id === p.id && JSON.stringify(it.variant || {}) === JSON.stringify(variant));
      if (idx >= 0) { const copy = [...c]; copy[idx] = { ...copy[idx], qty: copy[idx].qty + qty }; return copy; }
      return [...c, { id: p.id, qty, variant }];
    });
    showToast(`${p.name.slice(0, 30)} added to cart`);
  };
  const buyNow = (p, qty = 1, variant = {}) => { addToCart(p, qty, variant); nav("checkout"); };
  const toggleWish = (id) => setWishlist(w => w.includes(id) ? w.filter(x => x !== id) : [...w, id]);
  const clearCart = () => setCart([]);

  const cartActions = { onAddCart: addToCart, onBuyNow: buyNow, onToggleWish: toggleWish };
  const cartCount = cart.reduce((s, i) => s + i.qty, 0);

  const doSearch = () => { if (searchQ.trim()) nav("listing", { q: searchQ.trim() }); };

  return (
    <div style={{ fontFamily: "'Inter',sans-serif", color: T.ink, background: T.bg, minHeight: "100vh" }}>
      <style>{`
        ${FONT_IMPORT}
        * { box-sizing: border-box; }
        body { margin: 0; }
        ::selection { background: ${T.teal}; color: #fff; }
        .hide-scrollbar::-webkit-scrollbar { height: 0; }
        input, select, button { font-family: 'Inter', sans-serif; }
        input:focus, select:focus { outline: 2px solid ${T.teal}44; }
        a { color: inherit; }
        @media (max-width: 900px) {
          .hero-grid { grid-template-columns: 1fr !important; }
          .hero-cards { display: none !important; }
          .cat-grid { grid-template-columns: repeat(4,1fr) !important; }
          .testi-grid { grid-template-columns: 1fr 1fr !important; }
          .footer-grid { grid-template-columns: 1fr 1fr !important; }
          .pdp-grid { grid-template-columns: 1fr !important; }
          .pdp-lower { grid-template-columns: 1fr !important; }
          .cart-grid { grid-template-columns: 1fr !important; }
          .account-grid { grid-template-columns: 1fr !important; }
          .admin-grid { grid-template-columns: 1fr !important; }
          .admin-lower { grid-template-columns: 1fr !important; }
          .stat-grid { grid-template-columns: 1fr 1fr !important; }
          .checkout-2col { grid-template-columns: 1fr !important; }
        }
        @media (max-width: 600px) {
          .cat-grid { grid-template-columns: repeat(3,1fr) !important; }
          .testi-grid { grid-template-columns: 1fr !important; }
          .footer-grid { grid-template-columns: 1fr 1fr !important; }
          .stat-grid { grid-template-columns: 1fr !important; }
        }
      `}</style>

      <Navbar nav={nav} cartCount={cartCount} wishCount={wishlist.length} searchQ={searchQ} setSearchQ={setSearchQ} onSearchSubmit={doSearch} onLogoClick={() => nav("home")} />

      {page === "home" && <HomePage nav={nav} cartActions={cartActions} />}
      {page === "listing" && <ListingPage nav={nav} params={params} cartActions={cartActions} wishlist={wishlist} />}
      {page === "product" && <ProductDetailPage id={params.id} nav={nav} cartActions={cartActions} wishlist={wishlist} />}
      {page === "cart" && <CartPage cart={cart} setCart={setCart} nav={nav} wishlist={wishlist} toggleWish={toggleWish} />}
      {page === "wishlist" && <WishlistPage wishlist={wishlist} nav={nav} cartActions={cartActions} />}
      {page === "checkout" && <CheckoutPage cart={cart} nav={nav} clearCart={clearCart} />}
      {page === "account" && <AccountPage params={params} nav={nav} wishlist={wishlist} cartActions={cartActions} />}
      {page === "admin" && <AdminPage nav={nav} />}

      {page !== "admin" && <Footer nav={nav} />}

      {toast && (
        <div style={{ position: "fixed", bottom: 24, left: "50%", transform: "translateX(-50%)", background: T.navy, color: "#fff", padding: "12px 20px", borderRadius: 12, fontSize: 13.5, fontWeight: 600, display: "flex", alignItems: "center", gap: 8, zIndex: 999, boxShadow: "0 12px 28px rgba(0,0,0,.25)" }}>
          <CheckCircle2 size={16} color={T.teal} /> {toast}
        </div>
      )}
    </div>
  );
}
